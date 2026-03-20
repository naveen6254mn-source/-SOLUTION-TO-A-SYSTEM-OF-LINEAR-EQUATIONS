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

Write a program to find a solution to a system of linear equations x-3y=0, 3x+y=10
```
import numpy as np
A=[[1,-3],[3,1]]
B=np.array([0,10])
c = np.linalg.solve(A,B)
print(c)

```
## Output:

<img width="462" height="172" alt="Screenshot 2026-03-16 154702" src="https://github.com/user-attachments/assets/326f407b-0b6a-42d4-9ed9-164cc170f1c7" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

