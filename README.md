
![GitHub Stars](https://img.shields.io/github/stars/0xAnsR/40-Days-Python)
![GitHub Forks](https://img.shields.io/github/forks/0xAnsR/40-Days-Python)
![GitHub Watchers](https://img.shields.io/github/watchers/0xAnsR/40-Days-Python)


# 40-Days-Python


## Day 2
# Python Essentials Guide

Welcome to the essentials of Python! This guide covers key concepts with examples to help you get comfortable with Python programming.

---

### Operators in Python
Operators perform calculations and comparisons in Python.

**Example:**
```python
# Arithmetic operators
a = 10
b = 5
print(a + b)  # Output: 15 (addition)
print(a * b)  # Output: 50 (multiplication)
```

###Working with Strings
Strings are used to store text and can be manipulated using methods like slicing and concatenation.

Example:

```python
greeting = "Hello, World!"
print(greeting[0:5])       # Output: Hello (slicing)
print(greeting.lower())    # Output: hello, world! (lowercase conversion)
```
###Comments in Python
Comments make code more readable and are ignored during execution.

Example:

```python
# This is a single-line comment
'''
This is a multi-line comment
spanning multiple lines
'''
```
###Understanding Variables
Variables store data for later use and don't require a specified type in Python.

Example:

```python
Copy code
age = 25  # Integer
name = "Alice"  # String
print(name, "is", age, "years old.")  # Output: Alice is 25 years old.
```
###Getting Input from Users
The input() function allows you to get data from users.

Example:

```python
Copy code
name = input("Enter your name: ")
print("Hello, " + name)  # Output depends on the user's input
```
###Conditional Logic in Python
Conditional logic lets you run code based on conditions using if, elif, and else.

Example:

```python
Copy code
age = 18
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```
###Type Conversion
Type conversion changes data from one type to another.

Example:

```python
Copy code
age = "25"
age = int(age)  # Converts string to integer
print(age + 5)  # Output: 30
```
###Control Flow with If, Elif, Else
Python uses if, elif, and else for conditional branching.

Example:

```python
Copy code
score = 85
if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
else:
    print("Grade: C")
```
###Functions: Writing Reusable Code
Functions allow you to reuse code by defining tasks you can call anytime.

Example:

```python
Copy code
def greet(name):
    return "Hello, " + name

print(greet("Alice"))  # Output: Hello, Alice
```
###Loops in Python (For and While)
Loops repeat code; for loops iterate over sequences, and while loops repeat based on conditions.

Example (For Loop):

```python
Copy code
for i in range(3):
    print(i)  # Output: 0, 1, 2
Example (While Loop):

python
Copy code
count = 0
while count < 3:
    print(count)
    count += 1  # Output: 0, 1, 2
```
###Utilizing Python Libraries
Libraries provide pre-built functions, saving you from writing code from scratch.

Example:

```python
Copy code
import math
print(math.sqrt(16))  # Output: 4.0 (square root function from math library)
```
###Troubleshooting and Debugging
Errors are part of coding; use try-except to handle them.

Example:

```python
Copy code
try:
    result = 10 / 0
except ZeroDivisionError:
    print("You can't divide by zero!")  # Output: You can't divide by zero!
```


