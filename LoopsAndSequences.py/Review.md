Loops and sequence Review. 

Python list 

In python, the list data type is an ordered sequence of elements that can be composed of strings. 

Cities = ['los angesles', 'london', 'Tokyo']

Cities[0]


Creating Lists 

developer = 'Jessica'

print(list(developer))


- finding the length of a list: You can use the len() function to get the length of a list: 

numbers = [1,2,3,4,5]
len(numbers)


- List Mutability:Lists are mutable, meaning you can update any elementen. 

programming_languages = ['Python', 'Java', 'C++', 'Rust']
programming_languages[0] = 'JavaScript'
print(programming_languages) # ['JavaScript', 'Java', 'C++', 'Rust']

- Index Out of Range Error: If you pass in an index (either positive or negative) that is out of bounds. 

- Checking if an Element Exists in a List: The in keyword can be used to check if an element exists in a list:

programming_languages = ['Python', 'Java', 'C++', 'Rust']

'Rust' in programming_languages # True
'JavaScript' in programming_languages # False

- Unpacking Values from a List: Unpacking values from a list is a technique used to assign values from a list to new variables. Here is an example to unpack the developer list into new variables called name, age and job like this:


-LIST METHODS

