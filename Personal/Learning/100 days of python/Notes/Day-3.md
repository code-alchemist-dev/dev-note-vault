---
date: 2024-05-29
topic: fundamental concepts in programming part 3
course: https://youdemy.co/learn/course/100-days-of-code-the-complete-python-pro-bootcamp-free-download-course#/course/4517/lesson/4519
---


> [!NOTE] *Fundamental Concepts in Programming: Control Flow with `if` / `else` and Conditional Operators in Python*
> 
>  Control flow is a fundamental concept in programming that dictates the order in which instructions are executed. In Python, control flow can be managed using conditional statements such as `if`, `else`, and `elif`, along with conditional operators. These constructs allow your program to make decisions and execute different code blocks based on certain conditions.


## Concept

## `if` Statement

> [!NOTE] Description
>  The `if` statement allows you to execute a block of code only if a specified condition is true.

```python
age = 18

if age >= 18:
    print("You are an adult.")

```

## `else` Statement

> [!NOTE] Description
>  The `else` statement can be used in conjunction with `if` to execute a block of code when the condition in the `if` statement is false.

```python
age = 16

if age >= 18:
    print("You are an adult.")
else:
    print("You are not an adult.")

```



## `elif` Statement

> [!NOTE] Description
>  The `elif` (short for "else if") statement allows you to check multiple conditions. It's used when you need to handle more than two possible conditions.

```python
score = 85

if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
else:
    print("Grade: F")


```


## Nested `if` Statement

> [!NOTE] Description
> You can nest `if` statements within each other to handle more complex conditions.

```python
age = 20
has_id = True

if age >= 18:
    if has_id:
        print("You are allowed to enter.")
    else:
        print("You need an ID to enter.")
else:
    print("You are not allowed to enter.")


```


## Conditional (Ternary) Operator

> [!NOTE] Description
>  Python also supports a conditional (ternary) operator for a more compact syntax of `if` and `else` statements.

```python
age = 18

message = "You are an adult." if age >= 18 else "You are not an adult."
print(message)

```


## Conditional Operators

> [!NOTE] Description
>  Conditional operators are used to form conditions in `if`, `elif`, and `else` statements. Here are the main ones:
>  - **Equality operator ==**: Checks if two values are equal.
>  - **Not equal operator !=**: Checks if two values are not equal.
>  - **Greater than >**: Checks if the left value is greater than the right value.
>  - **Less than <**: Checks if the left value is less than the right value.
>  - **Greater than or equal to >=: Checks if the left value is greater than or equal to the right value.
>  - **Less than or equal to <=**: Checks if the left value is less than or equal to the right value.



```python
# Equality
x = 5
if x == 5:
    print("x is 5")

# Not equal
y = 10
if y != 5:
    print("y is not 5")

# Greater than
a = 7
if a > 5:
    print("a is greater than 5")

# Less than
b = 3
if b < 5:
    print("b is less than 5")

# Greater than or equal to
c = 5
if c >= 5:
    print("c is greater than or equal to 5")

# Less than or equal to
d = 4
if d <= 5:
    print("d is less than or equal to 5")


```



> [!NOTE] Summary
> *fundamental concepts in programming. overview:* 
> 
> Understanding and using control flow with `if`, `else`, and `elif` statements, along with conditional operators, is essential for making your Python programs dynamic and responsive to different inputs and conditions. These tools enable you to direct the flow of execution and create more complex and functional applications.

