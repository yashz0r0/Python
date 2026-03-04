
## Numbers and Strings



## 1. Numbers

Numbers are used to store numeric values in Python.

### Types of Numbers
- **int** → Integer numbers
- **float** → Decimal numbers
- **complex** → Complex numbers

---

## Integer Example

```python
x = 10
y = -5

print(x)
print(y)
```

---

## Float Example

```python
price = 99.99
temperature = 36.6

print(price)
print(temperature)
```

---

## Complex Number Example

```python
z = 3 + 4j

print(z)
print(type(z))
```

---

## Basic Operations with Numbers

```python
a = 10
b = 3

print(a + b)   # Addition
print(a - b)   # Subtraction
print(a * b)   # Multiplication
print(a / b)   # Division
print(a % b)   # Modulus
```

---

# 2. Strings

A **string** is a sequence of characters enclosed in quotes.

You can use:
- single quotes `' '`
- double quotes `" "`

---

## String Example

```python
name = "Yash"
message = 'Hello Python'

print(name)
print(message)
```

---

## String Indexing

Each character in a string has an index.

```python
text = "Python"

print(text[0])   # P
print(text[1])   # y
print(text[-1])  # n
```

---

## String Slicing

Slicing extracts a part of a string.

```python
text = "Python Programming"

print(text[0:6])
print(text[7:18])
```

---

## String Length

```python
text = "Python"

print(len(text))
```

---

## String Methods

### Uppercase

```python
text = "python"

print(text.upper())
```

### Lowercase

```python
text = "PYTHON"

print(text.lower())
```

### Replace

```python
text = "Hello World"

print(text.replace("World", "Python"))
```

### Split

```python
text = "Python is easy to learn"

print(text.split())
```

---

