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

class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length     
        self.__breadth = breadth  

    def display(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)


r1 = Rectangle(10, 5)


r1.display()

## Output
<img width="981" height="325" alt="image" src="https://github.com/user-attachments/assets/a8b2f2ce-fc4d-4250-bb45-c2f8d55f4b23" />

## Result
Thus, the program to demonstrate Encapsulation using private variables in Python is successfully executed.
