
## Create a List
A list is an ordered collection of items. You can create a list of different items by separating them with a comma and placing them between square brackets.
```python
fruits = ["apple", "banana", "cherry"]
```

## Accessing Items in a List
Use square brackets to access an item in a list, based on its position in the list.
```python
fruits = ["apple", "banana", "cherry"]
fruits[0] # result is "apple"
```

## Add an Item to a List
You can add an item to a list using the `append()` method. This will add the item to the end of the list.
```python
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
```

## Insert an Item into a List
You can insert an item at a specific position in a list using the `insert()` method.
```python
fruits = ["apple", "banana", "cherry"]
fruits.insert(1, "orange")
```

## Remove an Item from a List
You can remove an item from a list using the `remove()` method. This will remove the first occurrence of the item.
```python
fruits = ["apple", "banana", "cherry"]
fruits.remove("banana")
```

## Looping through a List
You can use a for loop to iterate through all the items in a list.
```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

## List Comprehension
List comprehensions provide a concise way to create lists.
```python
numbers = [x for x in range(10)]
```
