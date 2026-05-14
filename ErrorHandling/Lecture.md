What are some common error messages in python? 

common erros include syntaxErros, NameError, typeErros, IndexError and AttributeError. 

Here is an example of a SyntaxError:

print("Hello, world!")
# SyntaxError: unexpected EOF while parsing


Here is an example of a NameError:

print(name)
# NameError: name 'name' is not defined 


Here is an example of a TypeError:

5 + "5"
# TypeError: unsupported operand type(s) for +: 'int' and 'str'
You can't add an integer and a string together. Python raises a TypeError when you try to perform an operation on incompatible data types. 

Here is an example of an IndexError:

my_list = [1, 2, 3]
print(my_list[5])
# IndexError: list index out of range 


You're trying to access an index that doesn't exist in the list. Python raises an IndexError when you go out of bounds.



Here is an example of an AttributeError:

num = 42
num.append(5)
# AttributeError: 'int' object has no attribute 'append'
The int object doesn't have an append() method. Python raises an AttributeError when you try to use a method or property that doesn't exist for that data type.



How does exception handling work? 

It helps to anticipate, catch and respond to errors in a structured way. 

Python provides. 

# Try, except.else and finally. 

try: The block of code where you anticipate an error might occur.

except: This block runs if an error of the specified type is raised inside the try.

In this case, dividing by zero raises a ZeroDivisionError, which is then caught and handled.



# And here's an example also showing how to use the else and finally blocks: 


# How does exception handlin work? 

try, except, else and finally block to gratefully handle errors. 

try: 

x = 10/0 

except ZeroDivisionError:

 print("you cant divdide by zero")

 -Try: The block of code where you anticipate an error might occur. 
 - Except: tHIS BLOCK RUNS if an error of the specified type is raides inside the try. 
 - In this case, dividing by zero riases a Zero division Error, which is then caught and handled. 

 and heres an example also showing how to use the else and finally blocks. 

 try:
    x = 10 / 2
except ZeroDivisionError:
    print("You can't divide by zero!")
else:
    print('Division successful:', x)
finally:
    print('This block always runs.')

# What Is the Raise Statement and How Does It Work? 

Python's raise statement can be used in several ways to trigger exceptions. At its most basic, you can raise built-in exceptions or create custom error messages. Here's a simple example:  

