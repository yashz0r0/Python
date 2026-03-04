# Loops in Python

Loops are used to **execute a block of code multiple times**.

Python mainly has two types of loops:

1. **for loop**
2. **while loop**

---

# 1. For Loop

A **for loop** is used to iterate over a sequence like a list, string, or range.

## Syntax

```python
for variable in sequence:
    # code block
```

## Example

```python
for i in range(5):
    print(i)
```

Output

```
0
1
2
3
4
```

---

## Loop Through a String

```python
word = "Python"

for letter in word:
    print(letter)
```

---

## Loop Through a List

```python
numbers = [10, 20, 30]

for num in numbers:
    print(num)
```

---

# 2. While Loop

A **while loop** runs as long as the condition is true.

## Syntax

```python
while condition:
    # code block
```

## Example

```python
i = 0

while i < 5:
    print(i)
    i += 1
```

Output

```
0
1
2
3
4
```

---

# Loop Control Statements

## break

Stops the loop immediately.

```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

---

## continue

Skips the current iteration.

```python
for i in range(5):
    if i == 2:
        continue
    print(i)
```

---
