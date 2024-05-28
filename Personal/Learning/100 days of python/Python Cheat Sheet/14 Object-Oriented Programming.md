## Creating Classes
A class is like a blueprint for an object. It defines a type of object according to the methods and attributes it should have. When you create a class, you define its methods and properties.
```python
class Animal:
    def __init__(self, name):
        self.name = name

    def speak(self):
        print(f"{self.name} makes a sound")
```

## Creating Instances
An instance is a particular object created from a class. You can create multiple instances of the same class.
```python
dog = Animal("Dog")
cat = Animal("Cat")
```

## Inheritance
A class can inherit attributes and methods from another class. This allows you to reuse code and create more specific classes.
```python
class Dog(Animal):
    def speak(self):
        print(f"{self.name} barks")
```

## Polymorphism
Different classes can have methods with the same name, allowing for different implementations. This is known as polymorphism.
```python
class Cat(Animal):
    def speak(self):
        print(f"{self.name} meows")

animals = [Dog("Dog"), Cat("Cat")]
for animal in animals:
    animal.speak()
```

## Encapsulation
Encapsulation restricts access to certain attributes or methods. It is implemented by using an underscore `_` before the attribute or method name.
```python
class Car:
    def __init__(self, model):
        self._model = model

    def get_model(self):
        return self._model
```
