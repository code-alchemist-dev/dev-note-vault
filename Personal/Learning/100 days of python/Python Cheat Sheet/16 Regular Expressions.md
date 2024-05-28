
## Importing re Module
You need to import the `re` module to use regular expressions in Python.
```python
import re
```

## Matching Patterns
You can use the `match()` function to check if a string matches a pattern.
```python
pattern = r"\d+"
string = "123"
match = re.match(pattern, string)
if match:
    print("Match found")
```

## Searching Patterns
You can use the `search()` function to search for a pattern within a string.
```python
pattern = r"\d+"
string = "There are 123 apples"
match = re.search(pattern, string)
if match:
    print("Match found")
```

## Finding All Matches
You can use the `findall()` function to find all matches of a pattern within a string.
```python
pattern = r"\d+"
string = "There are 123 apples and 456 oranges"
matches = re.findall(pattern, string)
print(matches)
```

## Replacing Patterns
You can use the `sub()` function to replace all matches of a pattern with a replacement string.
```python
pattern = r"\d+"
replacement = "number"
string = "There are 123 apples and 456 oranges"
new_string = re.sub(pattern, replacement, string)
print(new_string)
```
