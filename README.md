# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
#Step1 : Step1 : Import the NumPy module to use built-in matrix calculation functions.
#Step 2: Create the matrix using np.array() and store it in a variable (for example, A).
#Step 3: Use np.linalg.inv(A) to find the inverse of the matrix and store the result in another variable (for example, X).
#Step 4: Print the inverse matrix to display the result.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Rakisha R
#RegisterNumber:212225230223
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result=np.linalg.inv(matrix)
print(result)
```
## Output:
<img width="1346" height="818" alt="image" src="https://github.com/user-attachments/assets/5580cd21-3b8d-4ebe-992e-0f094ec17118" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

