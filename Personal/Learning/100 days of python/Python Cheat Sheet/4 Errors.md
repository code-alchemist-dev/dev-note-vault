## Syntax Error
Syntax errors occur when your code does not make sense to the computer. This can happen due to misspellings, unmatched brackets, or missing commas.
```python
print(12 + 4))
# Error message:
# File "<stdin>", line 1
# print(12 + 4))
# ^ SyntaxError: unmatched ')'
```

## Name Error
This error occurs when there is a variable name that the computer does not recognize, usually due to a misspelling. Note that variable names are case-sensitive.
```python
my_number = 4
my_Number + 2
# Error message:
# Traceback (most recent call last):
# File "<stdin>", line 1, in <module>
# NameError: name 'my_Number' is not defined
```

## Zero Division Error
This error occurs when you try to divide by zero, which is mathematically impossible.
```python
5 / 0
# Error message:
# Traceback (most recent call last):
# File "<stdin>", line 1, in <module>
# ZeroDivisionError: division by zero
```
