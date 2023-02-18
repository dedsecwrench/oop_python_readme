# __new__ method in class

The "new" method is a special method in Python that is used to create new objects.

Think of it like building a toy. When you want to build a new toy, you start by creating the basic structure and adding parts to it until it is complete. Similarly, when you create a new object in Python, you start by using the "new" method to create the basic structure of the object.

Once the basic structure is created, you can then use other methods like "init" to add more details to the object and make it fully functional.

So, in short, "new" is a method in Python that helps create new objects by building their basic structure.

Let's say we want to create a class called "Person". We can use the "new" method to create a new instance of the "Person" class.

```
class Person:
    def __new__(cls):
        print("A new person is being created!")
        instance = super().__new__(cls)
        return instance

    def __init__(self):
        print("Initializing a new person.")

person = Person()
```

When we create a new instance of the "Person" class by calling person = Person(), Python will automatically call the "new" method to create the basic structure of the object. In this example, the "new" method prints the message "A new person is being created!" and then uses the built-in super() function to create a new instance of the "Person" class. Finally, the "new" method returns the new instance.

Once the basic structure of the object is created by the "new" method, Python then calls the "init" method to initialize the object and add more details to it. In this example, the "init" method prints the message "Initializing a new person.".
