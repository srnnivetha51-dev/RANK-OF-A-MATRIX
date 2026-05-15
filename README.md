# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: S R NIVEDHITHA
#RegisterNumber:212225240102
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[3,2,5],[1,1,2],[3,3,6]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
<img width="603" height="804" alt="Screenshot 2026-05-15 115103" src="https://github.com/user-attachments/assets/ea79818b-5e0c-4ee7-98f2-c2da83e6fa97" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

