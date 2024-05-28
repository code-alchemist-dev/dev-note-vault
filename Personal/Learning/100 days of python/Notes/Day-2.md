---
date: 2024-05-28
topic: fundamental concepts in programming part 2
course: https://youdemy.co/learn/course/100-days-of-code-the-complete-python-pro-bootcamp-free-download-course#/course/4517/lesson/4519
---
## Concept

## Data Types

> [!NOTE] Description
>  Data types in programming define the kind of data that can be stored and manipulated within a program. Common data types include integers, floating-point numbers, strings, booleans, lists, dictionaries, and more.

```python
# Integer
num = 10

# Floating-point number
pi = 3.14

# String
name = "Alice"

# Boolean
is_student = True

# List
numbers = [1, 2, 3, 4, 5]

# Dictionary
student = {"name": "Alice", "age": 20, "is_student": True}

```

## Numbers

> [!NOTE] Description
>  In programming, numbers can be of various types such as integers, floating-point numbers, and complex numbers.

```python
# Integer
integer_num = 42

# Floating-point number
float_num = 3.14159

# Complex number
complex_num = 2 + 3j

```

## Operations

> [!NOTE] Description
>  Operations in programming include arithmetic operations, comparison operations, logical operations, and more. These operations are used to manipulate data.

```python
# Arithmetic operations
a = 10
b = 5

addition = a + b       # 15
subtraction = a - b    # 5
multiplication = a * b # 50
division = a / b       # 2.0
modulus = a % b        # 0
exponentiation = a ** b # 100000

# Comparison operations
greater_than = a > b      # True
less_than = a < b         # False
equal_to = a == b         # False
not_equal_to = a != b     # True

# Logical operations
x = True
y = False

and_operation = x and y   # False
or_operation = x or y     # True
not_operation = not x     # False

```

## Type Conversion

> [!NOTE] Description
>  Type conversions (or type casting) involve converting one data type into another. This is useful when you need to perform operations that require specific data types.

```python
# Integer to float
int_num = 10
float_num = float(int_num)  # 10.0

# Float to integer
float_num = 10.5
int_num = int(float_num)    # 10

# String to integer
str_num = "123"
int_num = int(str_num)      # 123

# Integer to string
int_num = 123
str_num = str(int_num)      # "123"

```

## f-string

> [!NOTE] Description
>  f-strings (formatted string literals) in Python provide a way to embed expressions inside string literals, using curly braces `{}`. They are prefixed with `f` or `F`.

```python
name = "Alice"
age = 25

# Using f-strings to format a string
greeting = f"Hello, my name is {name} and I am {age} years old."
print(greeting)  # Output: Hello, my name is Alice and I am 25 years old.

# Expressions inside f-strings
calculation = f"5 + 3 = {5 + 3}"
print(calculation)  # Output: 5 + 3 = 8

# Formatting numbers
pi = 3.14159
formatted_pi = f"Pi to three decimal places: {pi:.3f}"
print(formatted_pi)  # Output: Pi to three decimal places: 3.142
```



> [!NOTE] Summary
> *fundamental concepts in programming. overview:* 
> Programming fundamentals include several key concepts that are essential for writing effective code. Data types categorize values into different forms, such as integers, floating-point numbers, strings, and booleans, which dictate how data is stored and manipulated. Numbers, specifically integers and floats, are used for mathematical operations like addition, subtraction, multiplication, and division. Operations in programming include arithmetic, comparison, and logical operations, enabling complex computations and decision-making. Type conversions allow for the transformation of one data type to another, facilitating operations between different types, such as converting a string to an integer. F-strings (formatted string literals) in Python provide a concise and readable way to embed expressions inside string literals using curly braces, enhancing string formatting and output readability. Understanding these concepts is crucial for developing robust and efficient programs.
