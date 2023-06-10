# Python 

Python is a popular high-level programming language that is widely used for web development, data analysis, artificial intelligence, and more. It is known for its readability and simplicity, making it a great language for beginners and experts alike.

* It was created by Guido van Rossum, and released in 1991

## Usage :
* web development (server-side)
* software development
* mathematics
* system scripting

## Variables : 
* Python has no command for declaring a variable
* A variable is created the moment you first assign a value to it
* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)
* A variable name cannot be any of the Python keywords
* Python allows you to assign values to multiple variables in one line (Make sure the number of variables matches the number of values, or else you will get an error)
* Variables that are created outside of a function are known as global variables (Global variables can be used by everyone, both inside of functions and outside)
* A variable with the same name inside a function, this variable will be local, and can only be used inside the function
* To create a global variable inside a function, you can use the global keyword

## Data Types :
  Python has the following data types built-in by default, in these categories:

  - Text Type :	str
  - Numeric Types :	int, float, complex
  - Sequence Types :	list, tuple, range
  - Mapping Type :	dict
  - Set Types :	set, frozenset
  - Boolean Type :	bool
  - Binary Types :	bytes, bytearray, memoryview
  - None Type :	NoneType

## Numbers :
There are three numeric types in Python:
  - int --- Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length
  - float --- Float, or "floating point number" is a number, positive or negative, containing one or more decimals
  - complex --- Complex numbers are written with a "j" as the imaginary part
  
** You cannot convert complex numbers into another number type.

## Strings :
Strings in python are surrounded by either single quotation marks, or double quotation marks.

* Slicing : You can return a range of characters by using the slice syntax -> [2:5]
* Upper Case : The upper() method returns the string in upper case
* Lower Case : The lower() method returns the string in lower case
* Remove Whitespace : Whitespace is the space before and/or after the actual text, and very often you want to remove this space
* Replace : The replace() method replaces a string with another string
* Split : The split() method returns a list where the text between the specified separator becomes the list items
* Capitalize : 	Converts the first character to upper case
* Count : Returns the number of times a specified value occurs in a string
* Endswith : Returns true if the string ends with the specified value
* Find : 	Searches the string for a specified value and returns the position of where it was found
* Join : 	Converts the elements of an iterable into a string
* Startswith : Returns true if the string starts with the specified value
  
### String Format :
The format() method takes the passed arguments, formats them, and places them in the string where the placeholders {}
