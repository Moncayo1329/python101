List, tuples and ranges which are three basic sequences types used in python 

List are mutable and use zeroo- based indexing, meaning that the first element of the list is at index zero. 

heres the basic syntax for a list 

cities = ['Los Angeles', 'London', 'Tokyo']

To acces an element from the citires list, you can reference it index number in the sequence. 

Here is an example of accesing the first element of the cities list: 

cities = [' Los Angeles', 'London', 'Tokyo']
cities[0] 


What are some common methods used for list? 

Some common methods associated with them like append(), pop() and sort(). 

append()method. This is used to add an item to the end of the list. Here is an example of using the append() method to add the number 6 to list of numbers: 

numbers = [1, 2, 3, 4, 5]
numbers.append(6)
print(numbers) # [1, 2, 3, 4, 5, 6]


The extend() method is similar to the append() method, but with extend() you can add multiple elements from one list to another. Here's an example of adding the numbers 6, 8, and 10 from one list to the end of the numbers list:

numbers = [1, 2, 3, 4, 5]
even_numbers = [6, 8, 10]

numbers.extend(even_numbers)
print(numbers) # [1, 2, 3, 4, 5, 6, 8, 10] 

To insert an element at a specific index in a list, you can use the insert() method. This method accepts two arguments: the index where you wish to insert the new item and the item you want to insert. 

numbers = [1, 2, 3, 4, 5]
numbers.insert(2, 2.5)

print(numbers) # [1, 2, 2.5, 3, 4, 5] 

If you want to remove an element from a list, you can use the remove() method. The remove() method takes the value of the element to remove as an argument: 

numbers = [10, 20, 30, 40, 50, 50]
numbers.remove(50)

print(numbers) # [10, 20, 30, 40, 50] 

