# Matrix-Differentiation-Operators
<p float="left">
<a href = "https://github.com/zaman13/Matrix-Differentiation-Operators/tree/master/Code"> <img src="https://img.shields.io/badge/Language-Python-blue" alt="alt text"> </a>
<a href = "https://github.com/zaman13/Matrix-Differentiation-Operators/blob/master/LICENSE"> <img src="https://img.shields.io/badge/license-MIT-green" alt="alt text"></a>
<a href = "https://github.com/zaman13/Matrix-Differentiation-Operators/tree/master/Code"> <img src="https://img.shields.io/badge/version-1.0-red" alt="alt text"> </a>
</p>

<p float="left">
<img align = "right" src="https://github.com/zaman13/Matrix-Differentiation-Operators/blob/master/Diff_1D.png" alt="alt text" width="480">

Finite difference matrix  operators for performing numerical differentiation in python. The current version can handle 1D and 2D numpy arrays. 2D arrays need to be reshaped/unraveled into a column vector first. Differentiation can be performed by pre-multiplying the vector with the matrix operator. After the matrix operation, it can be reshaped to its originial dimensions. The matrix operators use secord order central differene formula (except for edge points where second order forward/backward difference formula is used). The code uses sparse matrices and therefore can handle large arrays. 
</p>

## Features
- Differentiate numpy arrays using simple matrix multiplication.
- Differentiation of 1D and 2D data (in meshgrid format) have been implemented so far.
- The matrix operators are in the form of sparse matrices. So, the operators can handle large datasets.


### Package requirements
  - NumPy <a href = "https://docs.scipy.org/doc/numpy/reference/"> <img src="https://img.shields.io/badge/Pkg-NumPy-FF4500" alt="alt text"> </a>
  - SciPy (sparse matrices, sparse linear algebra) <a href = "https://docs.scipy.org/doc/scipy/reference/sparse.html"> <img src="https://img.shields.io/badge/Pkg-sparse-FF7F50" alt="alt text"> </a> <a href = "https://docs.scipy.org/doc/scipy/reference/sparse.linalg.html"> <img src="https://img.shields.io/badge/Pkg-sparse.linalg-FF7F50" alt="alt text"> </a>

## Use
The ```Differentiation_testing_v1.py``` file contains an example differentiation problem in 1D and 2D.

## Sample Output
The following plots show the first and second derivative of an one dimensional Gaussian function. The results obtained using the matrix operators are compared with the analytical results.

<p float="left">
<img src="https://github.com/zaman13/Matrix-Differentiation-Operators/blob/master/Diff_1D.png" alt="alt text" width="800">
</p>

The following plots show the first derivative of a two dimensional Gaussian function. The results obtained using the matrix operators are compared with the analytical results.

<p float="left">
<img src="https://github.com/zaman13/Matrix-Differentiation-Operators/blob/master/Diff_2D.png" alt="alt text" width="800">
</p>
