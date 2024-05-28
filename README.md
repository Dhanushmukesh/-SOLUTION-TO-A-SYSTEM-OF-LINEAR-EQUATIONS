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
import numpy as np
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
c=np.linalg.solve(a,b)
print(c)


## Output:
![Screenshot 2024-04-04 104455](https://github.com/Dhanushmukesh/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155508176/31d62311-ec3a-4b42-afd7-fea6cbc124e7)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

