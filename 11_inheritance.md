# Inheritance in Python

**Inheritance** allows one class to acquire the properties and methods of another class.

It helps in:
- Code reuse
- Better organization
- Creating hierarchical relationships between classes

The class being inherited from is called the **Parent Class (Base Class)**  
The class that inherits is called the **Child Class (Derived Class)**

---

# Basic Syntax

```python
class Parent:
    pass

class Child(Parent):
    pass
```

---

# Example of Inheritance

```python
class Animal:

    def __init__(self, name):
        self.name = name

    def speak(self):
        print("Animal makes a sound")


class Dog(Animal):

    def bark(self):
        print(self.name, "is barking")


d = Dog("Tommy")

d.speak()
d.bark()
```

Output

```
Animal makes a sound
Tommy is barking
```

The `Dog` class inherits the `speak()` method from `Animal`.

---

# Using super()

`super()` is used to call the constructor or methods of the parent class.

```python
class Person:

    def __init__(self, name):
        self.name = name


class Student(Person):

    def __init__(self, name, course):
        super().__init__(name)
        self.course = course


s = Student("Yash", "Computer Science")

print(s.name)
print(s.course)
```

---

# What is `self` in Python?

`self` represents the **current object (instance) of the class**.

Whenever a method inside a class is called, Python automatically passes the **object itself as the first argument**.

---

# Example of self

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display(self):
        print(self.name, self.age)


s1 = Student("Yash", 20)

s1.display()
```

Explanation:

- `self.name` refers to the object's name
- `self.age` refers to the object's age

So for object `s1`:

```
self.name = "Yash"
self.age = 20
```

---

# Why `self` is Important

`self` is used to:

1. Access instance variables  
2. Call other methods inside the class  
3. Differentiate instance variables from local variables

Example:

```python
class Counter:

    def __init__(self):
        self.count = 0

    def increment(self):
        self.count += 1
        print(self.count)


c = Counter()

c.increment()
c.increment()
```

Output

```
1
2
```

`self.count` stores the value inside the object.

---

