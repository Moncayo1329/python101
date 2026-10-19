is a programming style in wich developers treat everthing in their code like a real-world object 

A class is like a blueprint for creating objects 

Here's an example of a class that uses the __init__ special method to initialize the brand and color attributes whenever an object is created using the class:

class Car:
   def __init__(self, brand, color):
       self.brand = brand
       self.color = color  

# create two objects from the Car class
car1 = Car('Toyota', 'red')
car2 = Car('Lambo', 'green') 

print('Car 1 Brand:', car1.brand) # Car 1 Brand: Toyota
print('Car 1 Color:', car1.color) # Car 1 Color: red

print('Car 2 Brand:', car2.brand) # Car 2 Brand: Lambo
print('Car 2 Color:', car2.color) # Car 2 Color: green  

What Is Encapsulation? 

In that case, you can make deposit() and withdraw() public methods, and you hide the balance under the _balance attribute: 

class Wallet:
   def __init__(self, balance):
       self._balance = balance # For internal use by convention

   def deposit(self, amount):
       if amount > 0:
           self._balance += amount # Add to the balance safely

   def withdraw(self, amount):
       if 0 < amount <= self._balance:
           self._balance -= amount # Remove from the balance safely  


  Using a Double Underscore Prefix  

  prefixing attributes and methods with a double underscore effectively prevents them to be accessed from the outside of their class, making those attributes and methods private.  

  class Wallet:
   def __init__(self, balance):
       self.__balance = balance # Private attribute

   def deposit(self, amount):
       if amount > 0:
           self.__balance += amount # Add to the balance safely

   def withdraw(self, amount):
       if 0 < amount <= self.__balance:
           self.__balance -= amount # Remove from the balance safely

account = Wallet(500)
print(account.__balance) # AttributeError: 'Wallet' object has no attribute '__balance'  


You can also define a private __validate method to check if every deposit or withdrawal amount is a positive number:  

Defining Private Methods 

You can also define a private __validate method to check if every deposit or withdrawal amount is a positive number:  



