- creating objects : Objects are instances of a class. they are created by calling the class with the necessary arguments. 

dog1 = Dog('Jack', 3)
dog2 = Dog('Thatcher', 5)

dog1.bark()  # JACK says woof woof!
dog2.bark()  # THATCHER says woof woof!

- Calling Methods on Objects: You can call methods on objects to perform actions or retrieve information. 

object_name1.method_name()
object_name2.method_name()


Difference Between Class and Object: A class is a reusable template, while an object is a specific instance of that class with actual data.  

Attributes 

Instance Attributes: Defined in __init__() using self, and unique to each object.
Class Attributes: Defined directly inside the class and shared by all instances.

class Dog:
    species = 'French Bulldog'  # Class attribute  

def __init__(self, name):
        self.name = name  # Instance attribute 

print(Dog.species) # French Bulldog  

print(Dog.species) # French Bulldog

jack = Dog('Jack')
print(jack.name)     # Jack
print(jack.species)  # French Bulld   


Dunder (Magic) Methods
Definition: Special methods that start and end with a double underscore (e.g., __init__, __len__, __str__, __eq__). Python uses them internally for built-in operations.

class Book:
    def __init__(self, title, pages):
        self.title = title
        self.pages = pages

    def __len__(self):
        return self.pages

    def __str__(self):
        return f"'{self.title}' has {self.pages} pages"

    def __eq__(self, other):
        return self.pages == other.pages

book1 = Book('Built Wealth Like a Boss', 420)
print(len(book1))        # 420
print(str(book1))        # 'Built Wealth Like a Boss' has 420 pages