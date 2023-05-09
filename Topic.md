# Topic

## What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?
The major difference and the obvious one is that the class is the blueprint(template) or the sceleton of our objects, while the object is the instanses from that
class.

We put our variables and attributes that we want in our class, and then we create an object from that class, and this object will have these attributes and values.

## The concept of recursion and an best practice example of how it can be used to solve a problem in Python.
### Concept recursion in python : 
**Defintion :** A recursive function is a function defined in terms of itself via self-referential expressions.


This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result. All recursive functions share
a common structure made up of two parts: base case and recursive case.

### This is an example that calculates the factorial recursevely : 
        
        def factorial(x):
          if x == 1:
            return 1
          else:
            return (x * factorial(x-1))
    

         num = 3
         print("The factorial of", num, "is", factorial(num))
         




## The purpose of pytest fixtures and code coverage in testing Python code amd how they can be used together to improve the quality and maintainability of a project.
### Pytest
Pytest has a number of great features. One of those special features is fixtures. Using pytest fixtures to test your application is one way you can exponentially
increase code quality. 


Pytest is one of the most popular testing modules for Python.
### Pytest fixtures
Pytest fixtures are functions that can be used to manage our apps states and dependencies. Most importantly, they can provide data for testing and a wide range of value
types when explicitly called by our testing software. You can use the mock data that fixtures create across multiple tests.

