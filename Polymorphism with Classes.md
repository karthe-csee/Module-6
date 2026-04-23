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
```
class Beans:
    def type(self):
        return "Vegetable"
    def color(self):
        return "Green"
class Mango:
    def type(self):
        return "Fruit"
    def color(self):
        return "Yellow"
def describe(item):
    print("Type:", item.type())
    print("Color:", item.color())
    print()
b = Beans()
m = Mango()
describe(b)
describe(m)
```
## Output
<img width="377" height="288" alt="image" src="https://github.com/user-attachments/assets/0a95808b-d1b3-4a1a-99fc-c82179f87301" />

## Result
Hence the python program is executed sucessfully.

