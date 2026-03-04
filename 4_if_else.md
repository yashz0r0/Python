# If-Else Statement in Python

The **if-else statement** is used to make decisions in a program.

It executes a block of code **only if a condition is true**.

---

## Basic Syntax

```python
if condition:
    # code runs if condition is true
else:
    # code runs if condition is false
```

---

## Example

```python
age = 18

if age >= 18:
    print("You are eligible to vote")
else:
    print("You are not eligible to vote")
```

---

## If Statement Only

```python
number = 10

if number > 5:
    print("Number is greater than 5")
```

---

## If-Elif-Else Statement

Used when there are **multiple conditions**.

```python
marks = 75

if marks >= 90:
    print("Grade A")
elif marks >= 70:
    print("Grade B")
else:
    print("Grade C")
```

---

## Nested If Statement

```python
age = 20
has_id = True

if age >= 18:
    if has_id:
        print("Entry allowed")
    else:
        print("ID required")
else:
    print("Not allowed")
```

---

## Short-Hand If

```python
age = 20

if age >= 18: print("Adult")
```

---
