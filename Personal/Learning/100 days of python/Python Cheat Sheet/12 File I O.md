## Reading a File
You can open a file and read its contents.
```python
with open("file.txt", "r") as file:
    contents = file.read()
    print(contents)
```

## Writing to a File
You can open a file and write to it. This will overwrite the existing content.
```python
with open("file.txt", "w") as file:
    file.write("Hello, World!")
```

## Appending to a File
You can open a file and append to it. This will add new content to the existing file.
```python
with open("file.txt", "a") as file:
    file.write("\nNew line")
```

## Working with Files
When working with files, it is important to handle potential errors using try-except blocks.
```python
try:
    with open("file.txt", "r") as file:
        contents = file.read()
except FileNotFoundError:
    print("File not found")
```
