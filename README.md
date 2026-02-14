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
<img width="1215" height="864" alt="image" src="https://github.com/user-attachments/assets/4894b403-cb04-4226-90b8-2b2044e604e4" />

<img width="1234" height="569" alt="image" src="https://github.com/user-attachments/assets/6be43148-2878-4450-bcb6-6c850a313915" />

<img width="1223" height="858" alt="image" src="https://github.com/user-attachments/assets/e916de66-f4aa-4382-a1bd-456d9051f1ae" />

<img width="1235" height="316" alt="image" src="https://github.com/user-attachments/assets/2f9efea6-09a1-4089-a728-d864b0137ee4" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

