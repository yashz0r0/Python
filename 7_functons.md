# Functions in Python

A **function** is a block of code that performs a specific task.  
Functions help make programs **modular, reusable, and organized**.

---

# Defining a Function

Syntax:

```python
def function_name(parameters):
    # code block
```

Example:

```python
def greet():
    print("Hello, Python")

greet()
```

---

# Function with Arguments

Arguments allow you to pass data to a function.

```python
def greet(name):
    print("Hello", name)

greet("Yash")
```

---

# Function with Return Value

A function can return a value using `return`.

```python
def add(a, b):
    return a + b

result = add(5, 3)

print(result)
```

---

# Default Arguments

A parameter can have a default value.

```python
def greet(name="Guest"):
    print("Hello", name)

greet()
greet("Yash")
```

---

# *args (Arbitrary Arguments)

`*args` allows a function to accept **multiple positional arguments**.

```python
def add_numbers(*args):
    print(args)

add_numbers(1, 2, 3, 4)
```

Example with calculation:

```python
def add_numbers(*args):
    total = sum(args)
    print(total)

add_numbers(10, 20, 30)
```

---

# **kwargs (Keyword Arguments)

`**kwargs` allows a function to accept **multiple keyword arguments**.

```python
def student_info(**kwargs):
    print(kwargs)

student_info(name="Yash", age=20, course="Python")
```

Example accessing values:

```python
def student_info(**kwargs):
    print("Name:", kwargs["name"])
    print("Age:", kwargs["age"])

student_info(name="Yash", age=20)
```

---

