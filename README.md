# Python-Week-1
Python week-1 commences

# Basics of learning Python:
A basic unit of a program is called a variable or a container that holds a value in a program.
An equal sign is used as an assignment operator.
Variable names begin with letters(uppercase or lowercase), traditionally lowercase letters. Can have underscores and numbers but a variable name cannot start with a number.

# VARIABLES

There are several types of variables/data types in python
We have integers: which are whole numbers e.g 1,2.5,89,456 etc...

We have floats: which are decimal numbers e.g 0.5, 12.3, 453.03, 3.145 etc...

We have strings: which are a collection of characters e.g "car", "rabbit" etc...

We have complex numbers: which are used for complex mathematical calculations.

We have booleans: which have two values, true/false.

Working with strings, we can use the + sign to combine two strings. We call that concatenation.
Cannot be used to add string and numbers.

In Python we can also assign values to multiple variables in one line. x, y, z = "cat", "dog", "me".

Naming a variable:

* Cannot start with a number.
* Must start with an underscore or letter.
* Can contain alpha numeric characters and underscores (a-z,A-Z,0-9 & _).
* Variables are case-sensitive... Car and car are two different variables.

When declaring a variable in Python, you do not implicitly define its data type.


# Output variables
Python uses the print() funtion to output. Outputting multiple variables is separated by a comma inside the parenthesis.

# Global variables
Variables that are created outside of a function. Can be used inside and outside a function.

now creating a variable inside a function, we use the global keyword.


# DATA STRUCTURES
Data structures allow for the storage of a list of values in a single variable. which can contain any data type, including a list within a list.

Tuples are similar to lists, except they cannot be modified once declared.
Useful for storing large amounts of data more efficiently in memory.
A dictionary is a collection of key-value pairs, declared using a curly brace.

We have:
Lists - a collection which is ordered and changeable and allows duplicate members.

Tuples - a collection that is ordered and unchangeable and allows duplicate members.

Set - a collection which is unordered, unchangeable and unindexed and does not allow duplicate members.

Dictionary - a collection which is ordered and changeable but no duplicate members.

# LISTS
Used to store multiple items in a single variable.
Created using square brackets [].

List items are ordered, changeable, and allow duplicate values.

They are indexed, first item has index number of [0]

second item has index number of [1]

To determine how many items in the list, we use the len() function.

A list can have different data types. and can be of any data type

different data type - list1 = ["abc", 123, True, 3, "male"]

# OPERATORS
Instructions that perform operations on variables and values. Used to manipulate and perform actions on data.

* (+) - addition: used to add two values.
* (**) - multiply: used to multiple two values
* ^ - exponent: used as an exponent.
* / - divide: used as a division operator, returns a floating-point value even if result is a whole number..
* % - modulus: provides remainder after division
* // - floor division

Strings can also be manipulated, to concatenate we use the plus sign +.
To multiply a word certain number of times we used the multiplication sign.

Comparison operators, logical operators, identity operator and membership operator are another set of operators.

Comparison Operator: evaluate two values and produces a boolean result, either True/False. examples include double equal sign, less-than, less-than or equal-to, greater-than, greater-than or equal-to.

Logical operators: AND, OR & NOT 

operate on boolean values. The AND operator returns true if both operands are true, while the OR operator returns a true if either of the operands is true. The NOT operator negates the Boolean value it operates on.

Identity Operators:IS & IS NOT

used to compare two objects if they are they same objects in terms of memory location.


Membership operators: IN & NOT IN 

are used to check whether a value is present in a sequence or not. checks if a certain number or string exists in a given list or string.

Order of Precedence:
()- parenthesis
** - exponentiation
* - multiplication
/ - division
% - modulus
+ - addition
- - subtraction

# CONTROL FLOW
The if statement is one of three main types of control flow in programming and it allows you to execute a block of code if a certain condition is met.

Indentation is important because it determines the structure of the program. We also make use of loops in our programs. For Loop, While Loop, Do-While Loops.
We can use a for loop to iterate over a list or any iterable object.
A while loop keeps looking until a certain condition is false.

# FUNCTIONS

Functions can be defined by 'def' keyword, followed by the function name and arguments in parentheses, then colon ':'. inside the body of the function should be the code that defines what the function should do. along with a return keyword  to specify the output returned by the function. There is no curly brace that signifies the beginning and end of the function.

# BASIC DATA TYPES

# INTS & FLOATS

Converting from one data type to another is known as Casting.

There are 3 numeric types in Python:
* int - is a whole number, negative or positive.
* float - positive or negative numbers containing decimals
* complex - written with a "j" as the imaginary part.

converting from one type to another with int(), float(), complex() methods.

Python does not have a random() function to make a random number. We use a built-in module called 'random'.

Booleans

in Booleans, -1 is true, 0 is false. Anything excpet 0 is true.
boolean true is true.
anything other than an empty string is also true.
