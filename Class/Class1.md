How do classes work? 
A class is like a blueprint or template you use to create objects. 

To create a class you use the class keyword followed by the name of the class and a colon. 

Attibutes are like variables within a class,and are used to store data. methods are ffunctions defined within a class and are the actions objects create with a class can perform. 


class ClassName: 

   def__ init __ (self,name,age):
      self.name = name
      self.age = age 

    def sample_method(self): 
        print(self.name.upper()) 

        What are methods and attributes and how do they work

        There two types of class attributes how to acces from objects. 

        class Dog: 

         species = "french bulldog"


         def __init__(self, name):
         self.name = name #instance attribute. 


         What Are Special Methods and What Are They Used For?  
Special methods to make working with objects created from the book class easier: 


         How to Handle Object Attributes Dynamically?
 Python gives you four handy built-in functions to dynamically work with object attributes. They are getattr(), setattr(), hasattr(), and delattr().

 getattr() makes it possible to read an attribute from an object when you don't know its name until runtime. If the attribute doesn't exist, it raises an AttributeError, unless you provide a default value.   

 
 How to handle object attributes dynamically? 

 The brand and model could make attributes for a car class 

 class Car:  
       def __init__(self,brand, model): 
           self.brand = brand 
           self.model = model 

my_car = Car('Lamborghini', 'Gallardo')
print(my_car.brand)
print(my_car.model)

Python gives you four handy built-in functions to dynamically work with object attributes. They are getattr(), setattr(), hasattr(), and delattr().

getattr() makes it possible to read and attribute from an object when you dont know its name until runtime. 

The f string me permite insertar una varibale directamente dentro de un texto. 


