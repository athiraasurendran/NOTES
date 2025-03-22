# Control Flow

## IF
Used to execute a block of code only if a condition is true.
x = 10
if x > 5:
    print("x is greater than 5")

## IF-ELSE
Used when we want to execute one block if the condition is true and another if it is false.

x = 3
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")

## IF-ELIF-ELSE
Used when we have multiple conditions.

x = 10
if x < 5:
    print("x is less than 5")
elif x == 10:
    print("x is exactly 10")
else:
    print("x is greater than 5 but not 10")

## Nested IFs
An if statement inside another if statement.

x = 15
if x > 10:
    print("x is greater than 10")
    if x < 20:
        print("x is also less than 20")

# Loops

## For Loop
Used to iterate over a sequence (like a list, tuple, dictionary, or string).

fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

Using range() in a for loop

for i in range(5):  # Iterates from 0 to 4
    print(i)

## While Loop
Runs as long as the condition is true.

x = 0
while x < 5:
    print(x)
    x += 1

### Continue
Skips the rest of the current iteration and moves to the next.

for i in range(5):
    if i == 2:
        continue
    print(i)
    
Output: 0, 1, 3, 4 (skips 2)

### Break
Exits the loop immediately.

for i in range(5):
    if i == 3:
        break
    print(i)

Output: 0, 1, 2 (stops at 3)

# Basic Library Usage

## Keyword library
The keyword module provides a list of all Python keywords.

import keyword
print(keyword.kwlist)  # Prints a list of Python keywords

# Print formatting

## Placeholder passing
You can use placeholders {} with .format() or f-strings.

name = "Athira"
age = 24
print("My name is {} and I am {} years old.".format(name, age))
print(f"My name is {name} and I am {age} years old.")  # f-string method

## Multiline Assignment
Assign multiple values in a single line.

a, b, c = 1, 2, 3
print(a, b, c)

## Line-breaking
Python automatically breaks lines when inside parentheses (), brackets [], or braces {}.

numbers = [1, 2, 3, 4, 5, 6]
print(numbers)

We can also use \ for line continuation.

text = "This is a very long string that \ continues in the next line."
print(text)
