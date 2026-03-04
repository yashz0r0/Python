# Classes in Python

A **class** is a blueprint for creating objects.  
Classes are used in **Object-Oriented Programming (OOP)** to organize code.

An **object** is an instance of a class.

---

# Creating a Class

Syntax:

```python
class ClassName:
    # class body
```

Example:

```python
class Person:
    name = "Yash"

p1 = Person()

print(p1.name)
```

---

# __init__ Method (Constructor)

The `__init__()` method is a special function that runs automatically when an object is created.

```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

p1 = Person("Yash", 20)

print(p1.name)
print(p1.age)
```

---

# Instance Methods

Methods are functions defined inside a class.

```python
class Student:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print("Hello", self.name)

s1 = Student("Yash")
s1.greet()
```

---

# Modifying Object Properties

```python
class Person:
    def __init__(self, name):
        self.name = name

p1 = Person("Yash")

p1.name = "Rahul"

print(p1.name)
```

---

# Deleting Object Properties

```python
class Person:
    def __init__(self, name):
        self.name = name

p1 = Person("Yash")

del p1.name
```

---

# Deleting an Object

```python
class Person:
    pass

p1 = Person()

del p1
```

---
