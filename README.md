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

**INTS & FLOATS**

Converting from one data type to another is known as Casting.

There are 3 numeric types in Python:
* int - is a whole number, negative or positive.
* float - positive or negative numbers containing decimals
* complex - written with a "j" as the imaginary part.

converting from one type to another with int(), float(), complex() methods.

Python does not have a random() function to make a random number. We use a built-in module called 'random'.

Dividing ints will give a float result. Same as multiplying or adding an int to a float.

**ALTERNATIVE NUMBER TYPES**

If you pass a number as a string, the int class will convert it to an integer. 

Python has a number class called Decimal.

**Booleans**

in Booleans, -1 is true, 0 is false. Anything excpet 0 is true.

boolean true is true.

anything other than an empty string is also true.

The bool() function allows you to evaluate any value and returns either True/False.

**Most Values are True**

Almost any value is evaluated to true if it has some sort of content. 

Any string is true, except an empty string. Any number is true, except 0.

Any list, tuple, set and dictionary are true except empty ones.

e.g

bool("abc")

bool(123)

bool(["apple", "cherry", "banana"])

**Some Values are False**

There are not many values that evaluate to False, except empty values, such as (), [], {}, and the number 0 and the value none. The alue False, evaluates to False.

e.g
bool(False)

bool(None)

bool(0)

bool("")

bool(())

bool([])

bool({})

If you have an object that is made from a class with a __len__ function that returns 0 or False.

class myClass():
  def __len__(self):
  return 0

myObj = myClass()
print(bool(myObj))

We also have an function that return a boolean value, like the isinstance() funtion, which determines if an object is of a certain data type.

e.g this one checks if an object is an integer or not

x = 200
print(isinstance(x, int))

**Strings**

In Python, strings are surrounded by single, double or triple quotes. "hello" / 'hello'
Display the text via the print() function.

three signle/double quotes is used for a mutliline string message.

To check if a certain phrase is present in a string, we use the 'in' keyword.
To check if a certain phrase is NOT present in a string, we use the 'not in' keyword.

**SLICING**

You can use the slice syntax to return a range of characters.

get characters from position 2 to position 5
b = "hello world!"
print(b[2:5])

**SLICE FROM THE START**
get the characters from the start to position 5
b = "hello world!"
print(b[:5])

**SLICNG AT THE END**
get the characters from position 5 to the end
b = "hello world!"
print(b[2:])

We also have methods in the string class, namely: 

* strip() method removes any whitespaces from beginning to end.
* lower() method return a string in lower case.
* upper() method returns a string in upper case.
* replace() method replaces a string with another string.
* split() method to split the string into substrings if it finds an instance of the operator.


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

**LIST ITEMS**
List items are ordered, changeable, and allow duplicate values.

They are indexed, first item has index number of [0]

second item has index number of [1]

**ORDERED**

when a list is ordered, it means that the items  have a defined order, and that order does not change.

If you add new items in the list, they will be placed at the end of the list.


**List Length**

To determine how many items in the list, we use the len() function.

e.g
thisList = ["apples", "banana", "cherry"]

print(len(thisList))

**List Item - Data Types**

A list can have different data types. and can be of any data type

different data type - list1 = ["abc", 123, True, 3, "male"]

**type()**

in python's perspective, lists are defined as objects with the data type 'list'.

myList = ["apple", "banana", "cherry"]

print(type(myList))

**List() Constructor**

use the list() constructor when creating a new list.

thisList = list(("apple", "banana", "cherry"))

print(thisList)


Slicing can be used to get/ extract a range of values from a list or string, you can also add a third value to control the step size.
Range function can be used to generate a longer list which can also be sliced.
negative values can be used to step backwards through the list.
