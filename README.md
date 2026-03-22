# NAME: JAGAN J P
# REG.NO: 212224230099
# LU Decomposition 
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Input the coefficient matrix A of order n×n.
Step 2: Decompose the matrix A into two matrices L (lower triangular) and U (upper triangular) such that A=LU.
Step 3: Compute the elements of L and U using elimination method (store multipliers in L and resulting matrix in U).
Step 4: Display the matrices L and U

## Program:
(i) To find the L and U matrix
```
# Program to find L and U matrix using LU decomposition.
# Developed by: JAGAN J P
# RegisterNumber: 212224230099
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
# Program to solve a matrix using LU decomposition.
# Developed by: JAGAN J P
# RegisterNumber: 212224230099
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)
```

## Output (i):
<img width="879" height="323" alt="image" src="https://github.com/user-attachments/assets/586a7145-8898-440b-b0ef-b4059b5dacab" />
<img width="426" height="162" alt="image" src="https://github.com/user-attachments/assets/b8182283-2ed9-467a-b36d-f2bd0cc8bdfd" />

## Output (ii):
<img width="523" height="320" alt="image" src="https://github.com/user-attachments/assets/3b8bce9c-c2ca-4781-bc14-4fcd7b7f2f2f" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
