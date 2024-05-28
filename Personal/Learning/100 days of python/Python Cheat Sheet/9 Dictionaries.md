## Create a Dictionary
A dictionary is a collection of key-value pairs. Each key is connected to a value, and you can use the key to access the value.
```python
fruit_colors = {
    "apple": "red",
    "banana": "yellow",
    "cherry": "red"
}
```

## Accessing Items in a Dictionary
Use square brackets to access a value in a dictionary, based on its key.
```python
fruit_colors = {
    "apple": "red",
    "banana": "yellow",
    "cherry": "red"
}
fruit_colors["apple"] # result is "red"
```

## Add an Item to a Dictionary
You can add an item to a dictionary by specifying the key and value.
```python
fruit_colors = {
    "apple": "red",
    "banana": "yellow",
    "cherry": "red"
}
fruit_colors["orange"] = "orange"
```

## Remove an Item from a Dictionary
You can remove an item from a dictionary using the `del` keyword.
```python
fruit_colors = {
    "apple": "red",
    "banana": "yellow",
    "cherry": "red"
}
del fruit_colors["banana"]
```

## Looping through a Dictionary
You can use a for loop to iterate through all the key-value pairs in a dictionary.
```python
fruit_colors = {
    "apple": "red",
    "banana": "yellow",
    "cherry": "red"
}
for fruit, color in fruit_colors.items():
    print(f"The color of {fruit} is {color}")
```
