# 🐍 Python Variables – Complete Guide

## 🧠 1. What is a Variable in Python?

A **variable** is a name that refers to a **value stored in memory**. It acts like a container to hold data that can be used or modified later.

### Example:
```python
x = 10
name = "Namratha"
```

---

## 🎯 2. Why Use Variables?

Variables help you:

- Store values for later use
- Avoid repetition of values
- Improve readability
- Write dynamic and reusable code
- Enable calculations, decisions, and processing

---

## 🛠️ 3. How to Use Variables in Python

### Syntax:
```python
variable_name = value
```

Python is **dynamically typed** — no need to declare data types explicitly.

### Examples:
```python
age = 25           # Integer
pi = 3.14          # Float
name = "Alice"     # String
is_active = True   # Boolean
```

---

## ⚠️ 4. Rules for Naming Variables

- Must start with a **letter** (A–Z, a–z) or underscore `_`
- Can contain letters, digits (0–9), and underscores
- Cannot start with a number
- Case-sensitive (`Age` and `age` are different)
- Cannot use Python keywords (`class`, `if`, `def`, etc.)

### ✅ Valid:
```python
my_age = 30
_name = "Tom"
salary2023 = 70000
```

### ❌ Invalid:
```python
2nd_place = "John"  # starts with a number
def = 45            # uses keyword
first name = "Tom"  # space not allowed
```

---

## 📌 5. When and Where to Use Variables

Use variables whenever you need to:

- Store input or calculated values
- Avoid hardcoding
- Control logic via flags
- Pass values between functions or modules

---

## 🔁 6. Examples

### Basic Example:
```python
name = "Namratha"
age = 27
print(name, "is", age, "years old.")
```

### Calculations:
```python
num1 = 10
num2 = 5
sum = num1 + num2
print("Sum:", sum)
```

### User Input:
```python
user_name = input("Enter your name: ")
print("Hello", user_name)
```

### Boolean Logic:
```python
is_logged_in = True
if is_logged_in:
    print("Welcome back!")
```

### Reassignment:
```python
x = 10
x = x + 5
print(x)  # Output: 15
```

---

## 🧪 7. Variable Types in Python (Optional)

Common types:
- `int`: Integer
- `float`: Decimal number
- `str`: String
- `bool`: True/False
- `list`, `tuple`, `dict`, `set`: Collections

Check type:
```python
x = 10
print(type(x))  # <class 'int'>
```

---

## 💼 8. Interview Questions

### Q1: What is a variable in Python?
**A:** A variable is a named reference to a value in memory.

### Q2: What are the rules for naming variables?
**A:**
- Start with a letter or underscore
- No keywords
- No spaces or symbols
- Case-sensitive

### Q3: What is dynamic typing?
**A:** Python allows variable types to change at runtime:
```python
x = 5      # int
x = "Hi"   # str
```

### Q4: Difference between `=` and `==`?
**A:**
- `=` assigns value
- `==` checks equality

### Q5: Can variable names have `@`, `$`, `#`?
**A:** No. Only letters, numbers, and underscores are allowed.

### Q6: What happens with undefined variables?
**A:** Python throws a `NameError`.

### Q7: Can variables change type?
**A:** Yes. Python is dynamically typed.

---

## 🧭 9. Best Practices

- Use descriptive names: `user_age` > `ua`
- Use `snake_case`
- Constants should be uppercase:
```python
PI = 3.14159
```

---

## ✅ 10. Summary

| Concept   | Explanation                                 |
|-----------|---------------------------------------------|
| Variable  | A named reference to a value in memory      |
| Syntax    | `name = value`                              |
| Type      | Python auto-detects (int, str, float, etc.) |
| Rules     | Naming conventions to follow                |
| Use       | Store, reuse, manipulate data               |

---

## 🔄 Practice Problem

**Task:** Ask the user for their name and age. Print:

> `"Hello Alice, you will be 30 next year."`

### Solution:
```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))
next_age = age + 1
print(f"Hello {name}, you will be {next_age} next year.")
```
