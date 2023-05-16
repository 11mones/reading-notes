# Variable Scope in Python
Variable scope in Python determines the visibility and lifetime of a variable. There are two types of scope: local and global.

## Local Scope:

Variables defined within a function or block have local scope.
They are only accessible within that specific function or block.
Local variables are created when the function or block is executed and destroyed when it completes.
Each function or block has its own local scope.

ex:

    def my_function()
      x = 10  # Local variable
      print(x)
     my_function()  # Output: 10
  
  
  
  
  
## Global Scope:

Variables defined outside any function or block have global scope.
They can be accessed from anywhere in the program.
Global variables are created when they are defined and persist throughout the program's execution.
Modifying global variables inside a function affects their values globally, using the global keyword.

ex:

     y = 20  # Global variable

     def my_function():
       global y
       y += 5
       print(y)
      my_function()



The global keyword is used to indicate that a variable is in the global scope, allowing you to modify global variables inside a function.
The nonlocal keyword is used to declare that a variable is in the enclosing (non-local) scope, enabling access and modification of variables in the outer scope from within a nested function.

## Big(O) notation
Big O notation is important for analyzing and comparing algorithm efficiency. It quantifies how an algorithm's runtime or space requirements grow with input size. It helps us choose the best algorithm for a problem and identify areas for optimization.
