# FileIO & Exceptions

## What is the use of the WITH statement in Python?
In Python, the with statement replaces a try-catch block with a concise shorthand.



**It ensures closing resources right after processing them.** A common example of using the with statement is reading or writing to a file. A function or class that supports the with statement is known as a context manager



## Defference between read() and readline()
The read() will read the whole file at once and then print out the first characters that take up as many bytes as you specify in the parenthesis versus the readline() that will read and print out only the first characters that take up as many bytes as you specify in the parenthesis.






## Python Exception Handling : 
We use the try...except block to handle exceptions in Python.



Here's the syntax of try...except block:



        try:
    # code that may cause exception
        except:
    # code to run when exception occurs



### Explanitaion 
Here, we have placed the code that might generate an exception inside the try block. Every try block is followed by an except block.

When an exception occurs, it is caught by the except block. The except block cannot be used without the try block.

