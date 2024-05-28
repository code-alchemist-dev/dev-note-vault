## List Comprehensions
List comprehensions provide a concise way to create lists.
```python
numbers = [x for x in range(10)]
```

## Lambda Functions
Lambda functions are small anonymous functions defined using the `lambda` keyword.
```python
add = lambda x, y: x + y
print(add

(2, 3))
```

## Map Function
The `map()` function applies a function to all items in an iterable.
```python
numbers = [1, 2, 3, 4, 5]
squared = list(map(lambda x: x**2, numbers))
print(squared)
```

## Filter Function
The `filter()` function filters items in an iterable based on a function.
```python
numbers = [1, 2, 3, 4, 5]
even = list(filter(lambda x: x % 2 == 0, numbers))
print(even)
```

## Reduce Function
The `reduce()` function applies a function of two arguments cumulatively to the items of an iterable, from left to right, to reduce the iterable to a single value.
```python
from functools import reduce
numbers = [1, 2, 3, 4, 5]
sum = reduce(lambda x, y: x + y, numbers)
print(sum)
```

## Decorators
Decorators allow you to modify the behavior of a function or class method.
```python
def my_decorator(func):
    def wrapper():
        print("Something is happening before the function is called.")
        func()
        print("Something is happening after the function is called.")
    return wrapper

@my_decorator
def say_hello():
    print("Hello!")

say_hello()
```

## Generators
Generators allow you to iterate through a sequence of values. They are created using functions and the `yield` keyword.
```python
def my_generator():
    yield 1
    yield 2
    yield 3

for value in my_generator():
    print(value)
```

## Context Managers
Context managers allow you to allocate and release resources precisely when you want to. The most common use of context managers is in handling files.
```python
with open("file.txt", "w") as file:
    file.write("Hello, World!")
```
