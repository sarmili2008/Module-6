# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Obj
6. ects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
from abc import ABC, abstractmethod
import math

class type_shape(ABC):
    @abstractmethod
    def area(self):
        pass
    
class Rectangle(type_shape):
    def __init__(self,l,b):
        self.l = l
        self.b =b
    def area(self):
        return self.l*self.b
 class Circle(type_shape):
    def __init__(self,r):
        self.r = r
    def area(self):
        return 3.14*self.r*self.r
r = Rectangle(6, 4)
c = Circle(7)
print("Area of a rectangle:",r.area())
print("Area of a circle:",c.area())
## Output
Area of a rectangle: 24
Area of a circle: 153.86
## Result
Thus,the python program was run successfully for the given question
