# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the program 

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(matrixA)
print(rank)
```
## Output:
<img width="996" height="392" alt="Screenshot 2026-05-14 104748" src="https://github.com/user-attachments/assets/65394d46-b19d-4ec5-a585-0f89e75599b7" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

