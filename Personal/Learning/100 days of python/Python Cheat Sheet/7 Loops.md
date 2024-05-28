## While Loop
A while loop will keep repeating itself until the while condition becomes false.
```python
n = 1
while n < 100:
    n += 1
```

## For Loop
For loops provide more control than while loops. You can loop through anything that is iterable, such as a range, list, dictionary, or tuple.
```python
all_fruits = ["apple", "banana", "orange"]
for fruit in all_fruits:
    print(fruit)
```

## _ in a For Loop
If the value your for loop is iterating through is not needed, you can replace it with an underscore.
```python
for _ in range(100):
    # Do something 100 times.
```

## Break
This keyword allows you to exit the loop.

 When the computer reads `break`, it stops the loop completely.
```python
for n in range(20):
    if n == 15:
        break
    print(n)
```

## Continue
This keyword allows you to skip the current loop and proceed to the next iteration.
```python
for n in range(20):
    if n % 2 == 0:
        continue
    print(n)
```
