# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
class Beans: 
     type = "Vegetable"
     color = "Green"
class Mango:
    type = "Fruit"
    color = "Yellow"
def describe_object(obj):
    print(obj.type)
    print(obj.color)
bean = Beans()
mango = Mango()
print(bean.type)
print(bean.color)
print(mango.type)
print(mango.color)
## Output
Vegetable
Green
Fruit
Yellow
## Result
Thus,the python program was run successfully for the given question.
