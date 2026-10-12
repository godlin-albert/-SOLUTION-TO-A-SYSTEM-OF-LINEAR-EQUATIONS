# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np 
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
X=np.linalg.solve(A,B)
print(X)
<img width="1267" height="675" alt="image" src="https://github.com/user-attachments/assets/e4a33798-d018-4c8f-a517-14e315216af6" />


## Output:
<img width="1507" height="552" alt="image" src="https://github.com/user-attachments/assets/930cf3e7-2398-4c9a-ba7a-d1f320460d3e" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

