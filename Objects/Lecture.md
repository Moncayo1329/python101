How Do Classes Work and How Do They Differ From Objects? 

In python classes and objects work in hand to organizae and manager data. 

class ClassName:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def sample_method(self):               
        print(self.name.upper()) 


# What are methods and atributes and how do they work? 

in the last lesso, you learned about classes and how they act as blueprints for creating objects. 

Here, we will dive deeper into atributes and methods. 

Instance attributes are unique to each object created from a class, and you usually set them with the __init__ method. Class attributes, on the other hand, belong to the class itself and are shared by all instances of that class. 


# What Are Special Methods and What Are They Used For? 

