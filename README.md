# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
 Import the NumPy library for numerical operations.
### Step 2:
Define the coefficient matrix A and constant matrix B.
### Step 3: 
Use np.linalg.solve(A, B) to solve the system of linear equations.
### Step 4: 
Print the solution obtained from the solver.
## Program:

#Program to find the solution for the given linear equations.

#Developed by: Deepika.V

#RegisterNumber: 24000724

import numpy as np

A = np.array([[1, -3], [3, 1]])  # Coefficient matrix

B = np.array([0, 10])  # Constants on the right-hand side

solution = np.linalg.solve(A, B)

print(solution)

## Output:
![Screenshot 2025-04-26 205139](https://github.com/user-attachments/assets/672eae3a-3c53-4f34-933b-010b3abf7752)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

