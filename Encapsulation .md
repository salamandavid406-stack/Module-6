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
    def __init__(self, length=5, breadth=10):
        self.__length = length
        self.__breadth = breadth
        print("Output:")
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

rect = Rectangle()
Result = (rect._Rectangle__length, rect._Rectangle__breadth)


```
## Output
<img width="221" height="123" alt="image" src="https://github.com/user-attachments/assets/54f793d4-2375-4328-aa07-546aeb9cf004" />

## Result
Thus the program is run successfully
