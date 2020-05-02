# Matrix-Differentiation-Operators
Finite difference matrix  operators for performing numerical differentiation in python.

## Features
- Differentiate numpy arrays using simple matrix multiplication.
- Differentiation of 1D and 2D data (in meshgrid format) have been implemented so far.
- The matrix operators are in the form of sparse matrices. So, the operators can handle large datasets.

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
