---
date: 2024-05-27
topic: fundamental concepts in programming part 1
course: https://youdemy.co/learn/course/100-days-of-code-the-complete-python-pro-bootcamp-free-download-course#/course/4517/lesson/4519
---
## Concept

## Printing

> [!NOTE] Description
>  Printing in programming typically refers to displaying output to the console or terminal. It’s a way to communicate information to the user or to debug a program by showing the current state of variables.

```python
print("Hello, World!")
```


## Commenting

> [!NOTE] Description
>  Comments are annotations in the code that are not executed. They are used to explain and clarify the code for anyone reading it. Comments can help others understand your code and can also be useful for reminding yourself of what the code does.

```python
# This is a single-line comment

"""
This is a multi-line comment
that spans several lines.
"""

```


## String Manipulation

> [!NOTE] Description
>  String manipulation involves performing operations on strings to change their content, format them, or extract information. Common operations include concatenation, slicing, replacing, and formatting.


```python
# Concatenation
greeting = "Hello"
name = "Alice"
message = greeting + ", " + name + "!"
print(message)

# Slicing
substring = message[0:5]
print(substring)

# Replacing
new_message = message.replace("Alice", "Bob")
print(new_message)

# Formatting
formatted_message = f"{greeting}, {name}!"
print(formatted_message)
```


## Variables

> [!NOTE] Description
>  Variables are used to store data that can be referenced and manipulated in a program. They have names that can be used to access their stored values.

```python
# Variable assignment
age = 25
name = "Alice"

# Using variables
print(f"{name} is {age} years old.")

# Changing variable values
age = 26
print(f"{name} is now {age} years old.")
```


## Debugging

> [!NOTE] Description
>  Debugging is the process of finding and resolving errors or bugs in the code. This can involve checking the logic, fixing syntax errors, or finding runtime issues. Tools like debuggers, print statements, and logging can be used to assist in debugging..

```python
# Debugging with print statements
def add(a, b):
    print(f"a: {a}, b: {b}")  # Debugging statement
    return a + b

result = add(5, 3)
print(f"Result: {result}")
```


> [!NOTE] Summary
> *fundamental concepts in programming. overview:* 
> 
> In programming, understanding key fundamentals is essential for writing efficient and effective code. **Printing** is the process of displaying output to the console, aiding in communication and debugging. **Commenting** involves adding non-executable notes to the code to explain functionality, improving readability and maintenance. **Debugging** is the method of identifying and fixing errors in the code, often using tools and techniques like print statements and breakpoints. **String manipulation** includes various operations on strings, such as concatenation, slicing, and formatting, to modify and format textual data. Lastly, **variables** are used to store data values that can be referenced and manipulated, providing a way to work with dynamic information throughout a program. Together, these fundamentals form the backbone of programming, enabling developers to create, maintain, and debug code effectively.

