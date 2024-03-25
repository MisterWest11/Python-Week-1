# Functions

It is a block of code which executes only when it is called.

They are a handy way to creating blocks of code that you can reuse.

To define a function, you use the *def* keyword, followed by *function_name*, parentheses then the body of the function.

a function can one or more arguments.

**parameter vs argument**

a parameter is the variable listed inside the parentheses when defining a function.

an argument is the literal value passed to a function, when calling it for execution

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/b4e6bbf9-8766-4a5c-9b0b-80ae0ca6f23f)

**Lambda Functions**

A Python function that has only one expression and can't have multiple lines. It is meant to make it easier to create some small logic in one line instead of a whole function.

They are anonymous, meaning there is no need to name them.

*Basic Syntax*

use the *lambda* keyword, define parameters needed, use : to separate parameters from the expression

*lambda arguments: expression*

this example below is a lambda function with one parameter

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/3bc76eff-6715-4192-b5fc-17c5b9f2730d)



multiple parameter 

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/d48dcd9a-9a96-41b3-b0ac-bfecd3ea5676)


**Map function**

- applies a function to each item in an iterable (list, tuple, set or dictionary).

map(function, iterable)


**Filter() function**

Creates a collection of elements from an iterable for which a function returns

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/ac01a729-70e1-4493-a8d5-57d27f1e0638)


# Scope

in Python, there are two types of variables, Local variables which are defined inside the function. Global variables are defined outside the function in the main block.

**Locals()**

Variables defined within the scope of a function, are only accessible to the function and not anywhere outside the function.

**Global**

Variables defined in the main method, not within a function. used anywhere throughout the program.


# Classes & Objects

A class in a blueprint or real world representation of an object.
It contains attributes and method the class can possess. 

We have instance variables that contain data that is unique to each instance(object).

when creating a Class, we get a default function known as an *__init__()* function (constructor) which initializes an instance upon creation.

**Class Attributes and Methods**

Instance attributes are properties found in a class. 

Instance variables: attributes attached to an instance of a class. We define instance variables in the constructor ( the __init__() method of a class).

Class Variables: a variable that is declared inside a class.

Instance Methods: Used to access or modify the instance attributes.

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/4d94b5d7-91e8-4207-b15b-8a1e5637a6d3)


# Inheritance

When a subclass inherits attributes and functionalities of a parent class.

Class Methods: Used to access or modify the class state.

Static Methods: a method that performs a task in isolation. They don't have access to class attributes.

![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/e204c849-47a9-495e-895e-daf066585e2e)



# Exceptions

An error event that interrupts the flow of the program.

use a try-except method. in the *try* block, we have the code that is more likely to create an error in a program. in the *except* block, we handle our error in a smarter way, to help counter an interruption in our program flow.


![image](https://github.com/MisterWest11/Python-Week-1-4/assets/152319557/bd7baf24-e6b9-4c9c-9f04-f274b9abcf8a)

We also have the *finally* block that executes no matter an exception was found or not.
