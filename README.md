# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. From Scipy package import lu
3. Get input from the user 
4. Print result

## Program:
(i) To find the L and U matrix
Program to solve a matrix using LU decomposition.
Developed by:kabilan T
RegisterNumber: 22009071

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
 
 ````
 

## Output:



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

