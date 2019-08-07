## Python Tutorial
#### Author: Coffee-Fueled-Deadlines

## Introduction
  This tutorial is being created to assist in teaching the Python Programming Language to new members of the coding team.  This Tutorial will cover some basic elements of the language to include:
  
  1. **[Variables](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#variables)**
  1. **[Operators](https://github.com/Coffee-fueled-deadlines/PythonTutorial/blob/master/README.md#operators)**
  1. Statements
  1. Functions
  1. Classes
  1. Objects
  1. Properties
  1. Methods
  
  Each of the above topics can be clicked to bring you to that section of the tutorial.
  
## Variables
  
  A variable, as in mathematics, is a placeholder for information.  This information can take on different Types:
  
  * Integer
    An Integer is considered to be any whole number (positive or negative).
  * Float
    A Float is any number that is fractional (positive or negative) Examples: `3.5`, `.25`, `-7.20`
  * Boolean (Bool)
    A Boolean (commonly refered too as a Bool or a Bool Value) is either `True` or `False`
  * String
    A string is any length or assortment of Text or Numerical values that should be treated
    as numbers.  Examples: `"Cookie"`, `"3"`, `"A"`.  A string is defined in Python as being
    encompassed by single quotes `'` or doublequotes `"`.
    
  Python is a loosely typed language.  Typed, in this sense, is referring to the Variable Type (one of the above mentioned).  THis means that you do not have to specify the variable type prior to assigning a value to it as you would have to in some other Programming Languages.  For instance:
  
```Python
a = 10       # a is set to the Integer value of 10
a = "Cookie" # a is now set to the String value of Cookie
a = 0.53     # a is now set to the Float value of 0.53
a = True     # a is now set to the Boolean value of True
```

  As seen above, the variable `a` has been assigned and reassigned to all the different variable types without having to specify the type prior to it being set and re-set.  This is what defines a loosely typed language.
  
## Operators
  
  Python, as with all Programming Languages, uses a multitude of operators.  Many of these operators are identical to those used in other languages while others are expressed in a unique way in Python.  They will be listed in a table below:
  
| Operator | Description | Example |
| --- | --- | --- |
| + | The Addition operator.  This will add two variables together.  For Integers and Floats, it'll return the sum of the values.  For strings, it will return the two strings pieced together into one string.  | `a = 1 + 5` |
| - | The Subtraction operator.  This will subtract two Integer or Float values and give you the difference | `a = 5 - 3` |
| * | The Multiplication operator.  This will multiply two Integer or Float values and give you the product.  In addition, it can be used to multiple the number of times a string value is delivered/printed | `a = 1 * 5` |
| ** | The Exponent operator.  This will apply an exponent value to a string or float and return the value. | `a = 2 ** 3` |
| / | The Division operator.  This will divide two Integer or Float values and give you the quotient. | `a = 4 / 2` |
| = | The `set` or `equals` operator.  This operator DOES NOT behave how you might think it does.  This operator is used to set a Value to a Variable.  It does not check to see if two values are `equal to` one another. | `a = 5` |
| == | The `is equal to` operator.  This operator compares two values to see if they are equal.  If they aren't equal, it returns False.  If they are equal, it returns True. | `a = (5) == (4+1)` |
| != | The `does not equal` operator.  This operator compares two values to see if they are not equal.  If they aren't equal, it returns True, if they are Equal, it returns False (opposite of `==`) | `a = (5) != (3+50)` |

  Lets go more in depth with some of these operators and a general demonstration on how they are used:
  
```Python
name = "Bob Ross" # set the variable name to Bob Ross

if (name == "Jon Doe"): # The == operator checks if name is equal to "Jon Doe"
  print("Your name is Jon Doe")

else: # triggers only if the initial if statement is False
  print("Your name isn't Jon Doe, your name is " + name)
```

  If you where to input the above code into the Python Interpretor (IDE), you would get the result, "Your name isn't Jon Doe, your name is Bob Ross".  The reason for this is that the initial check on the If statement checked to see if the value of `name` was equal to `Jon Doe`.  But that is a False statement because we know that the value of `name` is `Bob Ross`.  So in this case, the `Else` part of the if statement triggers.  If this is confusing, don't worry!  We'll cover more on `if statements` later.
