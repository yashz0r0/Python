# Modules in Python

A **module** is a file that contains Python code such as functions, variables, and classes.

Modules help organize code and make it reusable.

Example: A Python file named `math_operations.py` is a module.

---

# Importing a Module

You can use the `import` keyword to use a module.

```python
import math

print(math.sqrt(16))
```

---

# Import Specific Functions

Instead of importing the entire module, you can import specific functions.

```python
from math import sqrt

print(sqrt(25))
```

---

# Import with Alias

You can give a module a shorter name using `as`.

```python
import math as m

print(m.sqrt(36))
```

---



# Creating Your Own Module

Step 1: Create a file named `mymodule.py`

```python
def greet(name):
    print("Hello", name)
```

Step 2: Use the module in another file

```python
import mymodule

mymodule.greet("Yash")
```

---

# Built-in Modules

Python has many built-in modules such as:

- `math`
- `random`
- `datetime`
- `os`
- `sys`

Example:

```python
import random

print(random.randint(1, 10))
```

---


# dir() Method

The `dir()` function is used to **list all the names (functions, variables, attributes)** defined inside a module.

Example:

```python
import math

print(dir(math))
```

This will display all available functions inside the **math module**, such as:

```
['acos', 'asin', 'atan', 'ceil', 'cos', 'factorial', 'floor', 'log', 'pi', 'sqrt', ...]
