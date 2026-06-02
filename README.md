# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: 
End the program
## Program:
```
#Program to find the inverse of a matrix.
#Developed by:  dharshini
#RegisterNumber: 212225220024
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([
    [1,0,3],
    [-1,2,-2],
    [2,3,-1]])
soln=np.linalg.inv(A)
print(soln)
```
## Output:
<img width="1350" height="393" alt="Screenshot 2026-06-02 201039" src="https://github.com/user-attachments/assets/345495c2-3082-4a13-9e64-59b1217cbbe7" />
## Result:
Thus the inverse of given matrix is successfully solved using python program

