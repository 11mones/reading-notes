# Testing and modules

## TDD (Test Driven Development)
**Definition :** is software development approach in which test cases are developed to specify and validate what the code will do. In simple terms, test cases
for each functionality are created and tested first and if the test fails then the new code is written in order to pass the test and making code simple
and bug-free.



It starts with creating the test cases that we want first, and then we write our code, and test it through these test cases, and if the code did not passed
the cases, then we have to keep editing our code until iy oasses all the tests.



## if __ name __ == '__main__' statement in Python :
**Short definition :** It allows You to execute code when the file runs as a script, but not when it’s imported as a module.




For most practical purposes, you can think of the conditional block that you open with if __ name __ == "__ main __ " as a way to store code that should only
run when your file is executed as a script.



## Concept recursion in python : 
**Defintion :** A recursive function is a function defined in terms of itself via self-referential expressions.



This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result. All recursive functions share
a common structure made up of two parts: base case and recursive case.




##
The main difference between a module and a package in Python is that a module is a simple Python script with a .py extension file that contains collections
of functions and global variables. In contrast, a package is a directory that contains a collection of modules, and this directory also contains
an __ init __ .py file by which the interpreter interprets it as a package.

### Building a module 
This is how you build a module : 



    def module_function(para):

        print("Creating a new Module: " + para)



### Importing packages 
To import a package, we type the following:



    import math 

