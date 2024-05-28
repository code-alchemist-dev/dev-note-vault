## Print Statements
One of the simplest ways to debug your code is to use print statements to display the values of variables at different points in your program.
```python
x = 10
print(f"x = {x}")
```

## Using a Debugger
Python has built-in support for debugging. You can set breakpoints, step through your code, and inspect variables.
```python
import pdb
pdb.set_trace()
```

## Handling Exceptions
You can use try-except blocks to handle exceptions in your code.
```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
```
