# Python Basics

A beginner-friendly guide covering core Python concepts including **strings**, **for loops**, **if/else**, **tuples**, and **lists**.

---

## 📘 Overview

This repository provides simple theory and examples to help beginners understand key Python topics.

----

## 🧵 1. Strings

Strings are sequences of characters used to store text. - Created using
single or double quotes. - Immutable.

### Example

``` python
text = "Hello Python"
print(text.upper())
```

---

## 🔁 2. For Loops

Used to iterate through sequences such as lists, strings, and ranges.

### Example

``` python
for i in range(5):
    print(i)
```

------

## 🔀 3. If / Else

Conditional statements that allow Python to make decisions.

### Example

``` python
num = 10
if num > 0:
    print("Positive")
else:
    print("Negative")
```

-----
## 🧺 4. Tuples
-   Ordered,Immutable ,Created using parentheses

### Example

``` python
info = ("Alice", 25, "Student")
print(info[0])
```
-----

## 📦 5. Lists

-   Ordered,Mutable,Created using square brackets

### Example

``` python
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
print(fruits)
```

## 📚 6. Dictionaries

- Dictionaries store data in key–value pairs.
- Mutable
- Unordered (but maintains insertion order in modern Python)
- Created using curly braces {}

Example

```
student = {
"name": "Alice",
"age": 20,
"course": "Python"
}


print(student["name"]) # Access value
student["age"] = 21 # Update value
student["grade"] = "A" # Add new key
print(student)
```

----
## 📝 Practice Exercises

-   Count vowels in a string
-   Print each item in a list
-   Check if a number is even or odd
-   Access tuple elements
-   Add or remove items from a list

----
