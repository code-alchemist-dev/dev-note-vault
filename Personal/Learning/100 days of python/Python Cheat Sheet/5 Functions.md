## Creating Functions
This is the basic syntax for defining a function in Python. It allows you to give a set of instructions a name, so you can trigger it multiple times without rewriting or copying it. The contents of the function must be indented.
```python
def my_function():
    print("Hello")
    name = input("Your name:")
    print("Hello")
```

## Calling Functions
You activate a function by calling it. This is done by writing the name of the function followed by parentheses. This allows you to determine when to trigger the function and how many times.
```python
my_function()
my_function()
# The function my_function will run twice.
```

## Functions with Inputs
You can give a function an input so that it can perform different actions based on the input. This makes your function more useful and reusable.
```python
def add(n1, n2):
    print(n1 + n2)

add(2, 3)
```

## Functions with Outputs
A function can also have an output, which is specified by the `return` keyword. This allows you to store the result from a function.
```python
def add(n1, n2):
    return n1 + n2

result = add(2, 3)
```

## Variable Scope
Variables created inside a function are destroyed once the function has executed. The location where you use a variable determines its value. Here, `n` is 2 outside the function, but inside `my_function()`, `n` is 3.
```python
n = 2
def my_function():
    n = 3
    print(n)

print(n) # Prints 2
my_function() # Prints 3
```

## Keyword Arguments
When calling a function, you can provide keyword arguments or just the values. Using keyword arguments allows you to provide inputs without following any specific order.
```python
def divide(n1, n2):
    result = n1 / n2

# Option 1:
divide(10, 5)
# Option 2:
divide(n2=5, n1=10)
```
