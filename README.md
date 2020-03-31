## Python Tutorial
#### Author: Coffee-Fueled-Deadlines

## Introduction
  This tutorial is being written by myself for two purposes.  First, I feel as though writing instructions helps to better myself as a programmer and I feel as though writing a guide that is decent enough to instruct another assists in my own personal growth.  While writing a tutorial, I find that I stumble upon little nuances of the language that I take for granted and doing so deepens my understanding.  Secondly, I'm writing this tutorial in an attempt to give an amateurs impression of the language.  I am not professionally taught and many of the things I've learned have been self-taught or self-studied.  Many things that a professional might take for granted, I had to learn the hard way.  And while this isn't always a good thing (Certain aspects of the way I write code might be wonky) I feel that other amateurs that are looking to better themselves as programmers can utilize my experiences and avoid the pitfalls that I myself have stumbled into many times.
  
  As stated, I am not a professional and I'm attempting to write this tutorial in layman's terms (or as close to it as possible).  If you notice that I've phrased anything in a way that in just plain wrong, please notify me.  I want this guide to be accurate, and to a degree, as technical as it can be without becoming unreadable and non-understandable to someone new to programming in general.
  
  I hope you enjoy it!
  
## Table of Contents  
  
  1. **[Variables](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#variables)**
  1. **[Operators](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#operators)**
      * Arithmetic Operators
      * Comparison
      * Logical Operators
      * Assignment Operators
  1. **[Conditional Statements](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#conditional-statement)**
  1. **[Loops](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#loops)**
  1. **[Lists](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#lists)**
  1. **[Dictionaries/JSON](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#dictionariesjson)**
  1. **[Functions](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#functions)**
  1. Classes
  1. Objects
  1. Properties
  1. Methods
  
  Each of the above topics can be clicked to bring you to that section of the tutorial.
  
---  
## Variables
  
>  A variable, as in mathematics, is a placeholder for information.  This information can take on different Types:
>  
>  * Integer
>    * An Integer is considered to be any whole number (positive or negative).
>  * Float
>    * A Float is any number that is fractional (positive or negative) Examples: `3.5`, `.25`, `-7.20`
>  * Boolean (Bool)
>    * A Boolean (commonly refered too as a Bool or a Bool Value) is either `True` or `False`
>  * String
>    * A string is any length or assortment of Text or Numerical values that should be treated
>      as numbers.  Examples: `"Cookie"`, `"3"`, `"A"`.  A string is defined in Python as being
>      encompassed by single quotes `'` or doublequotes `"`.
>    
>  Python is a loosely typed language.  Typed, in this sense, is referring to the Variable Type (one of the above mentioned).  THis >means that you do not have to specify the variable type prior to assigning a value to it as you would have to in some other Programming >Languages.  For instance:
>  
>```Python
>a = 10       # a is set to the Integer value of 10
>a = "Cookie" # a is now set to the String value of Cookie
>a = 0.53     # a is now set to the Float value of 0.53
>a = True     # a is now set to the Boolean value of True
>```
>
>  As seen above, the variable `a` has been assigned and reassigned to all the different variable types without having to specify the >type prior to it being set and re-set.  This is what defines a loosely typed language.
---  
## Operators
  
>  Python, as with all Programming Languages, uses a multitude of operators.  Many of these operators are identical to those used in >other languages while others are expressed in a unique way in Python.  They will be listed in a table below:
>
>---  
>### Arithmetic Operators
>
>>  Arithmetic Operators, in python, deal with adding, subtracting, multiplying, and dividing integers.  Also, the addition operator can >>be used in strings as well to include variables.  Listed below are some of the more common Arithmetic Operators.
>>  
>>| Operator | Description | Example |
>>| --- | --- | --- |
>>| + | The Addition operator.  This will add two variables together.  For Integers and Floats, it'll return the sum of the values.  For >>strings, it will return the two strings pieced together into one string.  | `a = 1 + 5` |
>>| - | The Subtraction operator.  This will subtract two Integer or Float values and give you the difference | `a = 5 - 3` |
>>| * | The Multiplication operator.  This will multiply two Integer or Float values and give you the product.  In addition, it can be >>used to multiple the number of times a string value is delivered/printed | `a = 1 * 5` |
>>| ** | The Exponent operator.  This will apply an exponent value to a string or float and return the value. | `a = 2 ** 3` |
>>| / | The Division operator.  This will divide two Integer or Float values and give you the quotient. | `a = 4 / 2` |
>>| // | The Floor Division operator.  This will divide two Integer or Float Values and give you the quotient as a floor value (without >>the remainder included). | `a = 4 // 3` |
>>| % | The Modulus Operator.  This will give you the remainder of two divided Integer or Float Values. | `a = 7 % 3` |
>>
>>  As a side note, the `Addition Operator` is frequently used with strings in the following manner:
>>```python  
>>name = "Willie Nelson"
>>
>>print("Your name is not " + name)
>>```
>>
>>  This works as it is essentially Adding the name value to the string provided in the `print` statement.
>---
>### Comparison Operators
>
>>  Comparison Operators, in python, are operators that compare two values or statements; such as checking if one value is greater than >>or equal to another.  Below are some examples of Comparison Operators:
>>  
>>| Operator | Description | Example |
>>| --- | --- | --- |
>>| == | The `is equal to` operator.  This operator compares two values to see if they are equal.  If they aren't equal, it returns >>False.  If they are equal, it returns True. | `a = (5) == (4+1)` |
>>| != | The `is not equal to` operator.  This operator compares two values to see if they are not equal.  If they aren't equal, it >>returns True, if they are Equal, it returns False (opposite of `==`) | `a = (5) != (3+50)` |
>>| < | The `Less Than` operator.  This operator compares two values (or statements) to see if the left section is less than the right >>section; if so it equates to `True` | `a = 4 < 6` |
>>| > | The `Greater Than` operator.  This operator compares to value (or statements) to see if the left section is greater than the >>right section; if so it equates to `True` | `a = 5 > 3` |
>>| <= | The `Less Than or Equal To` operator.  This operator behaves the same as the `<` operator but also checks if the values are the >>same; if so it equates to `True` | `a = 5 <= 5` |
>>| >= | The `Greater Than or Equal To` opeartor.  This operator behaves the same as the `>` operator but also checks if the values are >>the same; if so it equates to `True` | `a = 3 >= 3` |
>
### Assignment Operators

  In python, `Assignment Operators` are operators that are responsible for setting and adjusting the value of a variable.  Listed below are some Assigment Operators that you're likely to encounter:
  
| Operator | Description | Example |
| --- | --- | --- |
| = | The `set` or `equals` operator.  This operator DOES NOT behave how you might think it does.  This operator is used to set a Value to a Variable.  It does not check to see if two values are `equal to` one another. | `a = 5` |
| += | The `Append/Increment` operator.  This operator serves two independent functions.  It can be used to increment the value of an integer ( if `i = 0` and we use the `+=` operator as such: `i += 1`, the value of 1 has been incremented by 1).  In addition, it can be used to append string values to the end of strings (Assume `msg = "Hello "` we can append to that string as such `msg += "Bobby"`). | `a += 2` |
| -= | The `Decrement` operator.  This operator is used to decrease the value of an integer.  It does not work with string values. | `a -= 2` |

  Lets go more in depth with some of these operators and a general demonstration on how they are used:
  
```Python
name = "Bob Ross" # set the variable name to Bob Ross

if (name == "Jon Doe"): # The == operator checks if name is equal to "Jon Doe"
  print("Your name is Jon Doe")

else: # triggers only if the initial if statement is False
  print("Your name isn't Jon Doe, your name is " + name)
```

  If you where to input the above code into the Python Interpretor (IDE), you would get the result, "Your name isn't Jon Doe, your name is Bob Ross".  The reason for this is that the initial check on the If statement checked to see if the value of `name` was equal to `Jon Doe`.  But that is a False statement because we know that the value of `name` is `Bob Ross`.  So in this case, the `Else` part of the if statement triggers.  If this is confusing, don't worry!  We'll cover more on `if statements` later.

## Conditional Statement

  In Python, a Conditional statement is generally an `if/else` statement.  Essentially it's running one section of code if the condition is met or another section of code if it is not met.  There are also `if/elif/else` statements, which allow for more conditional checks on information.  I will give some examples below:
  
```python
a = 1

if a == 1:
    print("a is 1")
    
elif a == 2:
    print("a is 2")
    
else:
    print("a is something else!")
```

  Using the above code, try changing the value of `a` and see which section of code triggers.  By default, as it's written now, this code will print onto the screen, "a is 1" because the value of a is 1 and that conditional check matches.
  
## Loops

  A Loop is a section of code designed to repeat a set amount of time or indefinitely (Infinite Loop).  One should be cautious using Infinite Loops, however, and should generally integrate in a system that allows the program to eventually stop itself.  An example of some loops are below:

**For Loop**
```Python
# Lets count to ten
for i in range(10):
    print(i)
```

  You'll notice that this prints the numbers 0 to 9 on your screen.  This is because python begins counting at 0.  To remedy this, you could do `print(i+1)`.
  
**While Loop**
```python
i = 0
while i >= 10:
    print(i)
    i += 1
```

  You may have noticed that with this particular while loop, instead of counting from 0 to 9, it counted from 0 to 10 instead.  This is because of the operand `>=` (less than or equal to).
  
## Lists

  A list, in python, is an unordered, unkeyed, changeable assortment of strings, integers, floats, lists, and dictionaries that allows for repeat values.  There isn't much that can't be stored in a list.  A few examples of a list are below:
  
```python
# List of Integers
myListOfNumbers = [1,2,3,4,5,6,7,8,9]

# List of Strings
myListOfStrings = ['hi','how','are','you']

# A list of other lists
myListOfLists = []
myListOfLists.append(myListOfNumbers)
myListOfLists.append(myListOfStrings)
```

  Checking a list for a value is simple and there are a few ways to do it.  One is to iterate through the list and compare values:
  
```python
myListOfNumbers = [1,2,3,4]

for i in range(len(myListOfNumbers)):
    if myListOfNumbers[i] == 3:
        print('3 is in myListOfNumbers')
```

  However, a much simpler way of doing it is this:
  
```python
myListOfNumbers = [1,2,3,4]
number = 3

if number in myListOfNumbers:
    print(number, 'is in myListOfNumbers')
 ```
 
 ## Dictionaries/JSON
 
   Dictionaries, in python, are keyed, unsorted, lists of data that do not allow for dupicate keys.  A dictionary is a great way to store information that you want to access quickly.  A few examples of some dictionaries are as follows:
   
```python
myDictionary = {}
myDictionary['a'] = 'hello'
myDictionary['b'] = 'how'
myDictionary['c'] = 'are'
myDictionary['d'] = 'you'
 
print(myDictionary['c']) # prints the value of the Key 'c' (are)
 
# Dictionary key with a list for a value
 
myDictionary['e'] = ['how','are','you','doing']
print(myDictionary['e'])
```
 
   You can store many things in a dictionary to include strings, integers, lists, and even other dictionaries.
   
 ```python
 mainDict = {}
 subDict = {'name':'coffee-fueled-deadlines','age':28}
 
 mainDict['info'] = subDict
 
 print(mainDict['info']['name']) # Accesses the mainDict 'info' key and then accesses the subDict 'name'
 ```
 
   As a side note, python dictionaries are very close in structure to JSON.  Converting between the two is very easily done and chances are likely that you'll find yourself doing this somewhere along the line in your programming career.
   
```python
import json
 
mydict = {'name':'coffee-fueled-deadlines','age':28,'location':'secret'}
 
with open('./jsonfile.json','w') as jsonfile:
    json.dump(mydict, jsonfile, indent=4)
jsonfile.close()
```

  The above will write a file called `jsonfile.json` to the same directory that the python script is saved to.  If you open up this file, you'll see some lovely JSON in it that looks remarkably similar to a python dictionary.  Loading from a JSON file is just as easy:
  
```python
import json

with open('./jsonfile.json','r') as jsonfile:
    mydict = json.load(jsonfile)

print(mydict['name']) # You'll see the name value stored in that json file that we saved in the last step
```

## Functions

  In python, Functions are sections of code that are reusable and callable in later sections of your script.  They can be supplied arguments and often return a value, however they can be created in a way that accepts no variables and returns nothing but instead runs a predetermined set of instructions.  A few examples are below:
```python
# Lets make our function
def say_hello(name):
    print("Hello", name)

# Lets call our function
say_hello("Coffee-Fueled-Deadlines")

# Lets call it again with a new name
say_hello("Billy Joel")
```

  In addition, functions can accept named paremeters:
```python
# Lets use our say_hello function again
def say_hello(name):
    print("Hello", name)
    
# This time lets call it a bit differently
say_hello(name="Johnny Cash")
```

  If we'd like to REQUIRE our function to use named parameters, we can do this:
```python
# Oh look, our say_hello function again... but something is different now
def say_hello(*,name):
    print("Hello", name)

# This will throw an error
say_hello("Harry Potter")

# To use it, we have to call it like this now
say_hello(name="Harry Potter")
```

  In some cases, requiring named parameters can add clarity to a script.  Positional parameters have to be supplied in the correct order and any `None` values have to be specified.  With named parameters, you can have a complex-ish function as follows:
```python
# Our little person function
def a_person(*, name=None, age=None, location=None):
    person = {}
    if name:
        person['name'] = name
    else:
        person['name'] = 'Unknown'
    if age:
        person['age'] = age
    else:
        person['age'] = 'Unknown'
    if location:
        person['location'] = location
    else:
        person['location'] = 'Unknown'
    return str("Person's name is " + person['name'] + " they are " + person['age'] + " years old and are from " + person['location'])
    
# Lets call this function in a few ways
print(a_person())
print(a_person(name='Jimmy Hendrix', age='27', location='Wisconson?'))
print(a_person(name='Jimmy Hendrix'))
print(a_person(age='27'))
```

  We've essentially created a function that will return a value regardless of the variables we feed it.  However, these variables need to be named in order for it to function correctly.  In the above example, it would be incredibly difficult to exclude information with positional parameters instead of named parameters.
  
  Finally, we can also specify the Type of the parameter that we're expecting.  You can do this as follows:
```python
# Lets add some numbers
def add(a: int, b: int):
    return a + b
    
print( add(2, 6) ) # Should print 8
```

  Requiring a specific type can be important, at times.  For instance, if we didn't specify the type we wanted, something like this could happen:
```python
# Lets add some numbers
def add(a, b):
    return a + b

print( add("Hello","World") )
```

  While cool, this isn't quite the desired result from our function and unexpected behaviors should be eliminated from our code.  Specifying the type of variable we're expecting mitigates this issue.
  
  Now lets improve our little `add()` function.  Lets assume we want to add a BUNCH of numbers together, but lets also say that we don't exactly know how many the user will supply.  We can accomadate this as follows:
```python
def add(*numbers: int):
    total = 0
    for i in range(len(numbers)):
        total += numbers[i]
    return total

print( add(2,6,2) ) # Should return 10
```

  Our little `add()` function will now add all numbers supplied to it.  We accomplish this by adding an `*` in front of the parameter.  This tells our function to store the value in a `Tuple` (an immutable list).  We then iterate through this Tuple as though it where a list and add the numbers to the `total` variable in a `for loop` before returning the `total` variable.
