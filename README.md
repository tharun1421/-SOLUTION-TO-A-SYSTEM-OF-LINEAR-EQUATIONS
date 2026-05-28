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
from numpy import linalg
import numpy as np

A = np.array([[1, -3],
              [3,  1]])

B = np.array([0, 10])

solution = linalg.solve(A, B)

print(solution)

## Output:
<img width="1488" height="763" alt="Screenshot 2026-05-28 232000" src="https://github.com/user-attachments/assets/63987c7c-c9b6-481f-ac28-b71adae01e41" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

