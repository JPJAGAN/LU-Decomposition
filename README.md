# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
# Program to find L and U matrix using LU decomposition.
# Developed by: Harrish P
# RegisterNumber: 212224230088
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
# Developed by: Harrish P
# RegisterNumber: 212224230088
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
l,p=lu_factor(A)
x=lu_solve((l,p),B)
print(x)
```

## Output (i):
<img width="879" height="323" alt="image" src="https://github.com/user-attachments/assets/586a7145-8898-440b-b0ef-b4059b5dacab" />
<img width="426" height="162" alt="image" src="https://github.com/user-attachments/assets/b8182283-2ed9-467a-b36d-f2bd0cc8bdfd" />

## Output (ii):

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
