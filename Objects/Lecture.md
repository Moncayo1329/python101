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


# how to handle object attributes dynamucally 

Python give your four handly built-in functions to dynamically work with object attributes. They are getatte(), setattr(), hasattr() and delattr() 

They let you acces create check and remove attributes using variable names. 

getattr() makes it possible to read and attribute from an object when you dont know its name until runtime. if the atributte doesnt exist, it raises an atributeErros unless you provide a default value. 

# hasattr 

Is for chechin if the class existe before you delete or you do something with the attribute 

