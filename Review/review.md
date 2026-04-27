Variable
declarin Variables: To declare a variable use the assingment operator =
ejemplos
name = "Joe Doe"
age = 25 

Common Data types in python 
Integer = A whole number without decimal 
ejemplo : my_integer_var = 10 
          print('Integer:', my_integer_var)

float : A number with decimals: 

ejemplo: my_float_var = 4.50
         print('Float', my_float_var)


String: A sequence of character wrapped in quotes. 

ejemplo my_string_var = 'hello'
        print('String', my_string_var)


Boolean: A value representing either True or False: 
         my_booleand_var = True
ejemplo ('Boolean', my_booleand_var)


- Set: An unordered collection of unique elements: 

  my_set_var = {7,4,3}
  print('set', my_set_var)


- Dictionary: A collection of key_value pairs, enclosed in curly braces.

 ejemplo my_dictionary_var = {'name': 'Alice','age':25}

 print('Dictionary:' my_dictionary_var)

 - Tuple: An immutable ordered collection, enclosed in parentheses. 

 my_tuple_var = (7,8,9)
print('Tuple', my_tuple_var)

- Range A sequence of numbers often used in loops: 
my_range_var = range(5)
print(my_range_var) 

- list An ordered collection of elements that supporst different data types: 

ejemplo my_list = [22, 'hello world', 3.14, true]

print(my_list) 

- None: A special Value that represents the absence of a value: 
ejemplo my_none_var = None
       print('None', my_none_var)



** Immutable and mutable Types

These types cannot change once delared, although you can point their variables at something new, which is called reassignment. 

-- Mutable types: these types can change once declared, you can add, remove, or update their items. They include collection types such as list,set, and dictionary. 

type() function: to see the type for a variable, you can use the type()function like this: 

ejemplo 

greting = 'hello there'
age = 21

print(type(agreeeting))
print(type(age))

- isinstance() function this is used to check if a variable matches a specific data type: 

greeting = 'hello world'
name = 'john doe'

print(isinstance(gretting, str))
print(isinstance(name, int))
