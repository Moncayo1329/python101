What are getter and setters? 

getters and setters are methods that let you control how the atributtes of a class are accedes and modified. 

- with getters you retrieve a value 
- setter you set a value  

class Persona: 
    def __init__(self,nombre,edad):
    self.nombre = nombre
    self.edad= edad 


def get_edad(self): 
    return self.edad



persona = Persona("Carlos", 25)


print(persona.get_edad())


## que es un setter? 

Es un metodo que sirve para modificar el valor de un atributo. 

lass Persona:
    def __init__(self, edad):
        self.edad = edad

    def set_edad(self, nueva_edad):
        if nueva_edad >= 0:
            self.edad = nueva_edad
        else:
            print("Error: la edad no puede ser negativa.")


persona = Persona(25)

persona.set_edad(30)
print(persona.edad)

persona.set_edad(-10)
print(persona.edad)  


Creating Properties With the @property Decorator
In Python, a decorator is a function that modifies the functionalities of other functions, or classes, without changing their original code.

class Circle:
    def __init__(self, radius):
        self._radius = radius

    @property
    def radius(self): # A getter to get the radius
        return self._radius
  
    @property
    def area(self):  # A getter to calculate area
        return 3.14 * (self._radius ** 2)

my_circle = Circle(3)

print(my_circle.radius) # 3
print(my_circle.area) # 28.26   

Step 4
Add a __str__ method to the Employee class. Make it return an f-string with the format name: level, replacing name and level with the corresponding attributes.

After that, print charlie_brown to the console.


def __str__(self): 
 return f"{self.name}: {self.level} 


 Step 15
Create a class attribute named _base_salaries and assign it the following dictionary: 

{
    'trainee': 1000,
    'junior': 2000,
    'mid-level': 3000,
    'senior': 4000
}