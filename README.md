# Classes

class is created using "class" keyword
anytime you use a class, you're basically creating objects.
and here is the word objects as in object oriented programming or OOP
you create objects from classes.

class is like a blueprint for a house or a class is like a mold.
an object is when you use that blueprint to build a specific house.

so the class is again, the definition of new data type
The object is the incarnation of or technically instantiation of.

and another term for object would actually be an instance
you have instances of classes as well

you can define you own class which is your own datatype iside of it, 
and using dot notation you can store attributes inside of it

invoking a class in a normal function -
```
def ---():
      ...
      className()
```
this is generally known as constructor call.
this line of code constructs an object.
using synonyms, it is going to instantiate an object.

right it doesn't have anything inside of it, but it exist in the computer memory.

className.attribute

Q. is class object mutable or immutable ? 

A. they are mutable but we can make them immutable.

```
class ClassName:
      instance varibles
      attributes
      methods
```    

A methos is just a function inside of a class.
      
classes comes with certain methods and function inside of them that you can define and they just behave in a specific way.

These functions allow you tu determine behaviour in a standard way.

```
class ClassName:
      def __int__(self):
```      
        
Now inside of this "def __init__():" we can cutomize the class object.

This dunder init method is specifically known as instance method.
ans it's called exactly this "__init__" 
This is designed by the authors of Python.
and if you want to initialize the contents of an object from class, you define this method.


```
class ClassName:
      def __int__(self, name):
      self.name = name
```  

In this case we're adding the variables to objects, aka - instance variables to objects
This is just the authors of python chose to implement of an object in python.

if you wanna remember arguments which you passed in class constructor.
you've got to be able to those value somewhere.

but question is how do you store them in the current object that has just been instantiated.

The authors of the python decided that the convention is going to be that the init method,
also semi secretly takes a third argument i.e "self" that has to come first.

By convention it's called self, but you could call it technically anything you want, but the convention is to always call it self.
and self as it name implies.. gives you access to the current object that just created

newly created object which just exist in computer memory and has nothing.
it's up to you now you to store the variables passed as an arguments to the class, in the object.

Q. How do you do that ?

Python just automatically calls the dunder "__init__" method.
and it's gonna autamatically pass in a reference to an argument
that represents the current object that is just constructed in memory.

Inside of dunder '__init__' method you can literally create an attribute aka - instance variable... just like

`self.name = name`

Q. What is the differencce between "__init__" method and default constructor ?

A. In other laguages for instance - java there are functions that arre explicitly called constructors that construct the object.
They initialize the value,

Python technically calls this "__init__" method (the initialization method)
It initializes the values.




