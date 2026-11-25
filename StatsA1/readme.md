NumPy and Pandas: Array and Matrix Operations
Aim
To create a Pandas DataFrame, convert selected columns into a NumPy
array, explore array properties, perform arithmetic and matrix
operations, and calculate the inverse of a square matrix.
Requirements
- Python 3
- NumPy
- Pandas
Install the required libraries:
pip install numpy pandas
Program Overview
The program creates a DataFrame containing the names, ages, marks, and
gender of four students.

It then selects the Age and Marks columns and converts them into a
NumPy array called A.

The program demonstrates: - Array shape, size, and dimensions - Creating
a 2D NumPy matrix - Addition and subtraction of arrays - Element-wise
multiplication - Matrix multiplication - Transpose of a matrix - Inverse
of a square matrix
Concepts Demonstrated
1. DataFrame to NumPy Array
A = df[["Age", "Marks"]].to_numpy()
Selects the Age and Marks columns from the DataFrame and converts
them into a NumPy array.
2. Array Properties
- A.shape: Number of rows and columns; here, (4, 2).
- A.size: Total number of elements; here, 8.
- A.ndim: Number of dimensions; here, 2.
3. Arithmetic Operations
Matrices A and B have the same shape, so the program can perform: -
A + B: Element-wise addition - A - B: Element-wise subtraction -
A * B: Element-wise multiplication
4. Matrix Product
np.dot(A.T, B)
First transposes A. The resulting matrix has shape (2, 4).
Multiplying it by B, which has shape (4, 2), produces a (2, 2)
matrix.
5. Transpose
A.T
Interchanges the rows and columns of A.
6. Matrix Inverse
np.linalg.inv(C)
Calculates the inverse of matrix C. A matrix has an inverse only when
it is square and its determinant is non-zero. For the matrix in this
program, the determinant is 1, so the inverse exists.
How to Run
1. Save the Python program in a file, for example
   numpy_operations.py.
2. Open a terminal in the folder containing the file.
3. Run:
python numpy_operations.py
Expected Result
The program prints: - The NumPy array created from student ages and
marks - Its shape, size, and dimension - Matrix B - Addition,
subtraction, and element-wise multiplication results - The matrix
product of A.T and B - The transpose of A - Matrix C and its
inverse
Conclusion
This program demonstrates how Pandas and NumPy can be used to organise
tabular data and perform common numerical and matrix operations in
Python.
