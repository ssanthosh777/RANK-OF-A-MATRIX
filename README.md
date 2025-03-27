# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equation and assign in np.array
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: SANTHOSH S
#RegisterNumber: 212224100052
import numpy as np
A = np.array([[3, 2, 5], 
              [1, 1, 2], 
              [3, 3, 6]])

rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![Screenshot (123)](https://github.com/user-attachments/assets/3c5a37d5-2cb8-4d7c-b1a5-5f2b1581531f)


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

