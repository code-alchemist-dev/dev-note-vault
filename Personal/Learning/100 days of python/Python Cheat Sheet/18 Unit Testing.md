## Introduction
Unit testing is a method of testing individual units of source code to determine if they are fit for use.

## Using unittest
Python's built-in `unittest` module provides a framework for writing and running tests.
```python
import unittest

def add(x, y):
    return x + y

class TestAdd(unittest.TestCase):
    def test_add(self):
        self.assertEqual(add(2, 3), 5)

if __name__ == "__main__":
    unittest.main()
```

## Using pytest
`pytest` is a third-party testing framework that makes it easy to write simple and scalable test cases.
```python
def add(x, y):
    return x + y

def test_add():
    assert add(2, 3) == 5
```

## Test-Driven Development
Test-Driven Development (TDD) is a software development process where you write tests before writing the corresponding code.
1. Write a test.
2. Run the test and see it fail.
3. Write the code.
4. Run the test and see it pass.
5. Refactor the code.