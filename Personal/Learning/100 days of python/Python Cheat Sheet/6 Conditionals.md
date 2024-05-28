## If
This is the basic syntax for testing if a condition is true. If so, the indented code will be executed; otherwise, it will be skipped.
```python
n = 5
if n > 2:
    print("Larger than 2")
```

## Else
This specifies code that will be executed if the condition is false.
```python
age = 18
if age > 16:
    print("Can drive")
else:
    print("Don't drive")
```

## Elif
In addition to the initial `if` condition, you can add extra conditions to test if the first condition is false. Once an `elif` condition is true, the remaining `elif` conditions are skipped.
```python
weather = "sunny"
if weather == "rain":
    print("bring umbrella")
elif weather == "sunny":
    print("bring sunglasses")
elif weather == "snow":
    print("bring gloves")
```

## And
Both conditions on either side of the `and` must be true.
```python
s = 58
if s < 60 and s > 50:
    print("Your grade is C")
```

## Or
Either of the conditions on either side of the `or` must be true.
```python
age = 12
if age < 16 or age > 200:
    print("Can't drive")
```

## Not
This negates the original result of the condition. If it was true, it becomes false.
```python
if not 3 > 1:
    print("something")
# Will not be printed.
```

## Comparison Operators
These mathematical comparison operators refine your conditional checks.
```python
>  # Greater than
<  # Lesser than
>= # Greater than or equal to
<= # Lesser than or equal to
== # Is equal to
!= # Is not equal to
```
