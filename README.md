# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start with the matrix
Take the given matrix A.
2. Apply row operations
Use Gaussian elimination to convert 𝐴
A into an upper triangular matrix U.
The multipliers used in elimination will form the lower triangular matrix L.
3. Form L and U
U: the resulting upper triangular matrix
L: the matrix containing the multipliers (and 1’s on the diagonal)
4. Display the result
Print or output the L and U matrices.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: GOPINATH S
RegisterNumber: 25012981
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: GOPINATH S
RegisterNumber: 25012981
*/
```
'''Program to find L and U matrix using LU decomposition.
Developed by: GOPINATH S
RegisterNumber: 25012981
import numpy as np
from scipy.linalg import lu
a=eval(input())
b=np.array(a)
P,L,U=lu(b)
print(L)
print(U)
```

## Output:
<img width="1366" height="768" alt="Screenshot 2025-11-21 181034" src="https://github.com/user-attachments/assets/6e90e732-2b58-4abe-818f-cc0abe3fc2c9" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

