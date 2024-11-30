# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

## Step 1: Import the numpy module to use the built-in functions for calculation

## Step 2: Write the matrix as a list and assign in np.array()

## Step 3: Using the lu(), we can find the LU Decomposition of the given matrix.

## Step 4: End the program 

## Program:
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
## Output:
![Screenshot 2024-12-01 005601](https://github.com/user-attachments/assets/f1dbd881-0c36-4f38-aa89-0dcca1f893b4)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

