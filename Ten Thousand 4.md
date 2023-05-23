# Dunder methods

The purpose of dunder (double underscore) methods, also known as special methods or magic methods, in Python is to define behavior for built-in operations
and functionalities. These methods are called automatically by the Python interpreter in response to specific operations or syntax.

**Example :**


    class Node : 
        def __init__(self , data):
            self.data = data
            self.next = None 
    
# ethical issue concerning the use of developers’ work
    


The main ethical issue raised in the video was the unauthorized use of developers' work, specifically code plagiarism.
The AI guru was accused of taking existing open-source code, rebranding it as his own, and selling it without giving credit to the original developers.
This ethical issue could have been avoided by properly attributing the original developers, obtaining necessary permissions or licenses, and creating unique
content. Respecting intellectual property rights, giving proper attribution, seeking permissions, and developing original work are important practices to avoid
ethical issues related to using developers' work.



# Python statistics module



The Python statistics module is a part of the standard library that provides functions for performing statistical calculations. One commonly used function is mean(),
which calculates the average of a sequence of numbers. It takes a list of numbers as input and returns the mean value. Other functions in the module include median(),
mode(), stdev(), and variance(), which perform calculations for median, mode, standard deviation, and variance, respectively. The statistics module simplifies 
statistical operations in Python by providing pre-built functions for common calculations.


**Example :**

        import statistics

        data = [5, 10, 15, 20, 25]
        mean_value = statistics.mean(data)

        print("Mean:", mean_value)
