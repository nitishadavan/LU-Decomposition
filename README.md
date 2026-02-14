# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program.
2.Import the required libraries numpy and scipy.linalg.
3.Read the input matrix A from the user and convert it into a NumPy array.
4.Use the lu() function to decompose the matrix into P, L and U matrices.
5.Print the L and U matrices.
6.For solving AX = B, use lu_factor() to factorize matrix A.
7.Use lu_solve() to compute the solution vector X.
8.Print the solution.
9.Stop the program.

## Program:
(i) To find the L and U matrix
```
/*
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
![Uploading image.png…]()

![Uploading image.png…]()

![Uploading image.png…]()

![Uploading image.png…]()

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

