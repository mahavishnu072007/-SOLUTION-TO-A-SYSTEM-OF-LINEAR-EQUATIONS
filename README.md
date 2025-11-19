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
```
#program to find the solution for the given linear equation
#Developed by:MAHA VISHNU S
#register number:25018250

import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
X=np.linalg.solve(A,B)
print(X)
```
<img width="1264" height="689" alt="Screenshot 2025-11-19 105146" src="https://github.com/user-attachments/assets/ccf7ad4a-05a5-4a2b-b0ac-7f89b7810bd0" />

## Output:
<img width="1287" height="302" alt="image" src="https://github.com/user-attachments/assets/b7b00366-b723-4041-a38b-9670d604c752" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

