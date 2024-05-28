## Importing Modules
You can import a module to use its functions and variables in your code.
```python
import math
```

## Importing Specific Functions
You can import specific functions from a module.
```python
from math import sqrt
```

## Aliasing Modules
You can give a module a different name when importing it.
```python
import numpy as np
```

## Creating Modules
You can create your own modules by saving a Python file and importing it into another file.
```python
# In my_module.py
def greet(name):
    print(f"Hello, {name}")

# In another file
import my_module
my_module.greet("Angela")
```

## Built-in Modules
Python provides several built-in modules that you can use in your programs.
```python
import random
print(random.randint(1, 10))
```
