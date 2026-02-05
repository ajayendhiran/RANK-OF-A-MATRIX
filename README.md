# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array() 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by:A.jayendhiran 
#RegisterNumber:212225230115
import numpy as np 
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```

## Output:
<img width="1183" height="748" alt="Screenshot 2026-02-05 084432" src="https://github.com/user-attachments/assets/adb08df5-cdf6-4a77-b959-41283407c500" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

