# Python Lists

A **list** is used to store multiple values in a single variable.

Lists are:
- Ordered
- Mutable (can be changed)
- Allow duplicate values

---

## Creating a List

```python
numbers = [1, 2, 3, 4, 5]

print(numbers)
```

---

## List with Different Data Types

```python
data = [10, "Python", 3.14, True]

print(data)
```

---

## Accessing List Elements

Index starts from **0**.

```python
fruits = ["apple", "banana", "mango"]

print(fruits[0])
print(fruits[1])
print(fruits[2])
```

---

## Negative Indexing

```python
fruits = ["apple", "banana", "mango"]

print(fruits[-1])
print(fruits[-2])
```

---

## Changing List Elements

```python
fruits = ["apple", "banana", "mango"]

fruits[1] = "orange"

print(fruits)
```

---

## List Length

```python
numbers = [10, 20, 30, 40]

print(len(numbers))
```

---

## Adding Elements to List

### append()

```python
numbers = [1, 2, 3]

numbers.append(4)

print(numbers)
```

### insert()

```python
numbers = [1, 2, 4]

numbers.insert(2, 3)

print(numbers)
```

---

## Removing Elements

### remove()

```python
numbers = [1, 2, 3, 4]

numbers.remove(3)

print(numbers)
```

### pop()

```python
numbers = [10, 20, 30]

numbers.pop()

print(numbers)
```

---

## List Concatenation

```python
list1 = [1, 2]
list2 = [3, 4]

result = list1 + list2

print(result)
```

---
