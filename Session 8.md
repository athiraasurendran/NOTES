# Functions in Python

Functions in Python are reusable blocks of code that perform specific tasks. They help in organizing code, making it more readable and efficient. There are two types of functions in Python: built-in functions and custom functions.

## Built-in Functins

Python provides many built-in functions like print(), len(), sum(), etc. These functions perform common operations without requiring additional code.

print(len("Python"))

Output: 6

## Custom Functions

Users can define their own functions using the def keyword.

def greet(name):
    return f"Hello, {name}!"

print(greet("Athira"))

Output: Hello, Athira!

### Function arguments

Functions can take arguments (inputs) to perform operations.

def add(a, b):
    return a + b

print(add(5, 3))

Output: 8

### Default arguments

A function can have default values for parameters. If no value is provided, the default is used.

def greet(name="Guest"):
    return f"Hello, {name}!"

print(greet())

Output: Hello, Guest!

print(greet("Athira"))

Output: Hello, Athira!

### kwargs

**kwargs allows passing multiple keyword arguments as a dictionary.

def info(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")

info(name="Athira", age=24, city="Kochi")

Output: 
name: Athira  
age: 24  
city: Kochi  


### Function return values

Functions can return values using the return statement.

def square(n):
    return n * n

print(square(4))

Output: 16


