# Jupyter Lab and Jupyter Notebook
**Jupyter Lab and Jupyter Notebook are tools for interactive computing and data science.**

### Jupyter Lab:

* Modular and flexible interface
* Multiple Document Interface (MDI) with tabs
* Enhanced text editor with advanced features
* Integrated terminal for command-line operations
* Flexible layout and customizable workspace
* Support for a wide range of extensions



### Jupyter Notebook:

* Simple and easy-to-use interface
* Single document structure with cells
* Easy sharing of notebook files (.ipynb)
* Support for rich text elements and multimedia
* Suitable for interactive reports and tutorials


# NumPy library
**NumPy is a fundamental library that provides essential tools for scientific computing, numerical calculations, data manipulation, and data analysis in Python.
Its efficient array operations and extensive mathematical functions make it a valuable asset for various scientific and data-intensive tasks.**

Some of these tasks : 



* Multi-dimensional arrays for efficient storage and manipulation of data.
* Comprehensive collection of mathematical functions for array-based computations.
* Broadcasting capability for performing operations on arrays of different shapes.
* Vectorized operations that enhance performance and readability of code.
* Integration with other scientific computing libraries, forming a powerful ecosystem.
* Efficient memory management for handling large datasets.
* Convenient data manipulation features like slicing, reshaping, and combining arrays.
* Speed and performance due to its optimized C implementation.



## Structure of NumPy arrays


**Basic Structure and Properties of NumPy Arrays:**

* NumPy arrays are represented by the ndarray (n-dimensional array) object.
* Arrays have a shape that defines the dimensions, and each element has a fixed data type.
* The shape is a tuple of integers representing the size of each dimension.
* Arrays are homogeneous, meaning all elements have the same data type.


**Creating NumPy Arrays:**

      import numpy as np
      arr1d = np.array([1, 2, 3, 4, 5])
      arr2d = np.array([[1, 2, 3], [4, 5, 6]])
      zeros = np.zeros((3, 4))
      ones = np.ones((2, 3))
      range_arr = np.arange(0, 10, 2)
      random_arr = np.random.rand(3, 3)
