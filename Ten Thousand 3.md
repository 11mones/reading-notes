# List comprehesive
List comprehension is a concise way to create a new list in Python. It allows you to transform or filter elements from an existing iterable into a new lis
t using a compact syntax. The basic syntax includes an expression that defines the transformation, a variable for each item in the iterable, and an optional
condition to filter items. List comprehension eliminates the need for manual iteration and appending in a for loop. It provides a more concise and readable way
to create lists.

**Example : **


    numbers = [1, 2, 3, 4, 5]
    squared_numbers = [num ** 2 for num in numbers]
    print(squared_numbers)
    # Result : [1, 4, 9, 16, 25]
    
# Decorator in Python 
    
A decorator in Python is a way to modify the behavior of a function or class without directly changing its source code. It is denoted by the "@" symbol followed
by the decorator name and is placed above the function or class definition. Decorators provide a flexible and reusable approach to add functionality such as logging,
timing, authentication, or memoization to functions or classes. They promote code modularity and separation of concerns, allowing modifications to be applied to
multiple functions or classes easily. Decorators are widely used for code reuse, aspect-oriented programming, and metaprogramming in Python.


# Cases for decorator


**Common use cases for decorators include:**

 -Logging: Decorators can add logging statements to functions, allowing easy tracking of function calls and their arguments.

-Timing: Decorators can measure the execution time of functions, providing performance insights.

-Caching/Memoization: Decorators can cache function results based on their arguments, allowing faster subsequent calls with the same arguments.

-Authentication/Authorization: Decorators can enforce authentication or authorization checks before executing certain functions or methods.

-Validation: Decorators can validate function arguments or return values, ensuring data integrity.


**Example :**





          def uppercase_decorator(func):
            def wrapper():
              result = func()
              return result.upper()
            return wrapper

           @uppercase_decorator
          def greet():
            return "hello"

          print(greet())
