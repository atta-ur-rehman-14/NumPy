# Numpy(Numerical Python)
it is library of python that helps to handle large amount of data using arrays
# Features
- speed (5200 times faster than nomal python list)
- Less memory
- Easy Math operation
# Uses of Numpy
- Data Science
- ML & AI models(tensorflow and pytorch)
- Stock Market anf Finance
- Medical Research
- Image processing
- OpenCv
# Difference between in List vs Numpy
| Feature | Python List | NumPy Array |
| :--- | :--- | :--- |
| **Speed** | Relatively Slow. | **50-100x Faster** due to optimized C implementation. |
| **Memory Consumption** | Uses more memory (stores object references). | **High Memory Efficiency** (stores data in contiguous blocks). |
| **Calculations** | Requires loops (e.g., `for` loops) for operations. | Supports **Vectorized Operations** (direct element-wise math). |
| **Data Handling** | Suitable for small, general-purpose tasks. | **Best for Large Datasets** (handling millions of data points). |
| **Efficiency** | General-purpose data structure. | **Optimized** for scientific and mathematical computations. |
# Problems before making Numpy 
- Handle large amount of data is difficult
- using loop makes result delay in python
# Benifits
- Faster Calculation
- Easily handle millions of dataS
# Commands For Installing Numpy
1. Install [Vs Code](https://code.visualstudio.com/)
2. Open termiinal in Vs Code
3. Installling Numpy
```
Pip install numpy
```
# Arrays
it is cam collection pf number or values that can can store same time in a organized way.
OR
A NumPy array (also called `ndarray`) is a multidimensional, homogeneous collection of elements (all elements have the same data type), arranged in rows and columns.
# Syntax
```
np.array(object, dtype=None)
```
- `object` → list, tuple, or nested list
- `dtype` → (optional) defines data type (int, float, etc.)
# Arrays Ceating with default Values
## Zeros() Function
The `zeros() function` is used to create an array filled with all zero values.
### Syntax
```
np.zeros(shape)
```
- Shape means size of array
# Once() Function
The `ones() function` is used to create an array filled with all 1 values.
### Syntax
```
np.ones(shape)
```
# Full() Function
The full() function is used to create an array where all elements are filled with a specific value given by the user.
### Syntax 
```
np.full(shape, fill_value)
```
# 0D Array
A 0D array (zero-dimensional array) is an array that contains only one element.
It is also called a scalar array.
# syntax
```
np.array(value)
```
# 1D Array
A 1D array (one-dimensional array) in NumPy is a linear collection of elements arranged in a single row (like a list).It is also called vertex.
# Syntax
```
np.array([element1, element2, element3, ...])
```
# 2D Array
A 2D array is a collection of elements arranged in rows and columns.
It is also called a matrix.
# syntax
```
np.array([[row1], [row2], ...])
```
# Multi Dimensional Array
A multidimensional array is an array that has more than one dimension (i.e., 2D, 3D, etc.).It stores data in rows, columns, and layers.
# Syntax
```
np.array([[...], [...], ...])      # 2D
np.array([[[...]], [[...]]])       # 3D
```
### Uses
- Artificial Intelligence
- Deep Learning 
- MRI Scanning
- 3D model
# Creating Sequences of Number
## Arange() Function
The arange() function is used to create an array with evenly spaced values within a given range.It works like Python’s range() but returns a NumPy array.
# Syntax
```
np.arange(start, stop, step)
```
# Identity Matrix 
An identity matrix is a special type of square matrix in which:
- All diagonal elements = 1
- All non-diagonal elements = 0
It is used in mathematics and matrix operations.
# Syntax
```
np.eye(n)
```
OR
```
np.identity(n)
```
# eye() Function 
The eye() function is used to create a 2D identity-like matrix, where:
- Diagonal elements = 1
- All other elements = 0
 It is flexible because it can create rectangular matrices too.

