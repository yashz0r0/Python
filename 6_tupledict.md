# Tuples and Dictionaries in Python

---

# 1. Tuples

A **tuple** is used to store multiple values in a single variable.

Characteristics:
- Ordered
- Immutable (cannot be changed)
- Allows duplicate values
- Written using parentheses `()`

---

## Creating a Tuple

```python
numbers = (1, 2, 3, 4)

print(numbers)
```

---

## Tuple with Different Data Types

```python
data = (10, "Python", 3.14, True)

print(data)
```

---

## Accessing Tuple Elements

```python
fruits = ("apple", "banana", "mango")

print(fruits[0])
print(fruits[1])
print(fruits[2])
```

---

## Tuple Length

```python
numbers = (10, 20, 30, 40)

print(len(numbers))
```

---

## Tuple Concatenation

```python
tuple1 = (1, 2)
tuple2 = (3, 4)

result = tuple1 + tuple2

print(result)
```

---

# 2. Dictionaries

A **dictionary** stores data in **key-value pairs**.

Characteristics:
- Unordered
- Mutable
- Keys must be unique
- Written using curly braces `{}`

---

## Creating a Dictionary

```python
student = {
    "name": "Yash",
    "age": 20,
    "course": "Python"
}

print(student)
```

---

## Accessing Dictionary Values

```python
student = {
    "name": "Yash",
    "age": 20
}

print(student["name"])
print(student["age"])
```

---

## Adding Elements to Dictionary

```python
student = {
    "name": "Yash",
    "age": 20
}

student["college"] = "ABC University"

print(student)
```

---

## Updating Dictionary Values

```python
student = {
    "name": "Yash",
    "age": 20
}

student["age"] = 21

print(student)
```

---

## Removing Elements

```python
student = {
    "name": "Yash",
    "age": 20
}

student.pop("age")

print(student)
```

---
