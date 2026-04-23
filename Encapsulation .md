# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length  
        self.__breadth = breadth
    def get_length(self):
        return self.__length
    def get_breadth(self):
        return self.__breadth
    def set_length(self, length):
        self.__length = length
    def set_breadth(self, breadth):
        self.__breadth = breadth
    def calculate_area(self):
        return self.__length * self.__breadth
rect = Rectangle(5, 3)
print("Length:", rect.get_length())
print("Breadth:", rect.get_breadth())
print("Area:", rect.calculate_area())
rect.set_length(10)
rect.set_breadth(4)
print("Updated Area:", rect.calculate_area())
```
## Output
<img width="352" height="231" alt="image" src="https://github.com/user-attachments/assets/d9b39d33-06a5-4c68-9dc9-930c28ae9f53" />

## Result
Hence the python program is executed sucessfully.
