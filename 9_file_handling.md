# File Handling in Python

File handling allows a program to **create, read, write, and update files**.

Python provides built-in functions for working with files.

---

# Opening a File

Use the `open()` function.

Syntax:

```python
file = open("filename", "mode")
```

Example:

```python
file = open("example.txt", "r")
print(file.read())
file.close()
```

---

# File Modes

Common modes used while opening files:

- `"r"` → Read file
- `"w"` → Write file (overwrites existing content)
- `"a"` → Append to file
- `"x"` → Create new file
- `"b"` → Binary mode
- `"t"` → Text mode

Example:

```python
file = open("example.txt", "w")
file.write("Hello Python")
file.close()
```

---

# Reading a File

## read()

Reads the entire file.

```python
file = open("example.txt", "r")
print(file.read())
file.close()
```

---

## readline()

Reads one line at a time.

```python
file = open("example.txt", "r")
print(file.readline())
file.close()
```

---

## readlines()

Reads all lines and returns them as a list.

```python
file = open("example.txt", "r")
print(file.readlines())
file.close()
```

---

# Writing to a File

```python
file = open("example.txt", "w")
file.write("Learning Python file handling")
file.close()
```

---

# Appending to a File

```python
file = open("example.txt", "a")
file.write("\nThis line is appended")
file.close()
```

---

# Using with Statement

The `with` statement automatically closes the file.

```python
with open("example.txt", "r") as file:
    print(file.read())
```

---

