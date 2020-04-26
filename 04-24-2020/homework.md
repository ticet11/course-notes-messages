## Introduction to Programming with Python

**What is List Comprehension in Python?**

An elegant solution for defining and creating lists based on existing content.

**What is a Python Conditional and what is it used for?**

Conditionals are if/then statements that will perform some function in only certain conditions.

**What happens when you return a value for a python method/function**

If there isn't a defined return value, the default is to return None.

**What is a default argument and explain a use case.**

A default argument is a standard input for a function. Generally, if you have a function that will often take the same input with fewer instances of some alternate case, it would be easier to just use a default than have to continuously input the same input over and over again. 

Eg. if an input was color of jeans, I think it would make sense to make 'blue' the default argument.

**What is a named argument?**

A named argument is a more specific way to *name* an argument. 

Eg. run_about(distance=6, speed=4)

You could put them in a different order and it would still work, because they are named, but that isn't necessarily a good practice.

**What does the \*args do in a python function and how might you use it?**

*args allows you to input more arguments than what is specifically defined.

**What are Keyword Arguments in Python?**

**kwargs works similarly to *args, but the inputs are key/value pairs.

## Advanced Python Programming

**What is a Class in python?**
A class is an object.

**What is a dunder method in Python**
Dunder methods are predefined methods that can be used in your classes. They allow for operator overloading. These do not need to be invoked directly.

**What is self in python and how might we use it?**

self is an argument used in classes. It is used because when you create instances of a class, self will represent that new instance.

**How does inheritance work in python?**

Inheritance is when one object can use methods or properties past down from a parent object.

**What is pipenv?**

pipenv is a python environment. The goal is to create an environment that doesn't get effected by global updates. If a new update might have broken the program, it will continue to work with the same instances of all the dependencies initially defined in the pipenv.

**What is Polymorphism**

Polymorphism means a child class can inherit a method from a parent class and then alter that method (Method Overriding).

**What is the purpose of init in python**

init is how instances of a class are created. It binds the instance with attributes and arguments that are provided by the class and instance.

**What is a decorator and what is its purpose in python**

A decorator basically creates a modified instance of a method. The method itself isn't modified but it's behavior is altered with the decorator.

**What is a Generator in python**

A generator functions are able to create many single objects instead of one list full of items, for example.

**How do you declare a new instance of a class?**

variable = Class(arguments)

## Python API Development with Flask

**What is Flask?**

Flask is a Python web server application.

**What is an API?**

An API allows a developer to access data and/or features from the source of the API.

**What is the purpose of an API endpoint**

The API endpoint is where the API connects to the application.

**What is SQLite?**

A database managment system.

**Explain how you can use the HTTP verb POST**

Used to submit data to the server.

**Explain how you can use the HTTP verb GET**

Retrieves data from the server.

**Explain how you can use the HTTP verb PUT**

Used to update data already on the server.

**Explain how you can use the HTTP verb DELETE**

Used to remove data from the server.

**Explain what SQLAlchemy is?**

SQLAlchemy is an ORM that facilitates the communication between programs built in python and databases.
