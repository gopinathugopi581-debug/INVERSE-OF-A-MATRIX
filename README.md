# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import the numpy library. 
### Step 2:Create a matrix using np.array().
### Step 3:Find the inverse of the matrix using np.Linalg.inv(). 
### Steep 4:Diplay the inverse of the matrix using the print() statement.

## Program:#Program to find the inverse of a matrix.
#Developed by:Gopinath n 
#RegisterNumber:26007691

import os 

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=([[6,2,3],[3,1,1],[10,3,4]])

print(np.linalg.inv(A))
## Output:<img width="1232" height="777" alt="image" src="https://github.com/user-attachments/assets/b88ec8f9-b43e-4254-8049-c583252c9efe" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

