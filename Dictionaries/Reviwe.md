Dictionaries are built in data structures that store collections of key value pairs. keys need to be inmutable data types. 

dictionary = {
    key1 = value1, 
    key2 = value2. 

}

the keys and values methods return a view object with all the keys and values in the dictionary. 

Items the items method returns a view object with all the key values pairs in the dictionary. 

Clear() Removes all the keys-value pairs from the dictionary. 

pizza clear()

pop() Remove a key-value pair with the key specified as tghe first arguments. 


Looping over a dictionary 

Iterating over values: if you need to iterate over the values in a dictionary, you can write a fro loop with values() to get all the values a dictionary. 

products = {
    'Laptop': 990,
    'Smartphone': 600,
    'Tablet': 250,
    'Headphones': 70,
}

for price in products.values():
    print(price)


Sets are build structures in python that not allow duplicates values. 
SETS are mutable and unordered, wich mean that theu elements are not store in any specific order. 


Mathematical Set Operations
issubset() and issuperset() Methods: The issubset() and the issuperset() methods check if a set is a subset or superset of another set, respectively

isdisjoint() Method: The isdisjoint() method checks if two sets are disjoint, if they don't have elements in common. 

Union Operator (|): The union operator | returns a new set with all the elements from both sets.

Intersection Operator (&): The intersection operator & returns a new set with only the elements that the sets have in common.

