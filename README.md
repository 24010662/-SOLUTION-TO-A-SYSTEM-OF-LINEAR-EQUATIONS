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
#Program to find the solution for the given linear equations.
#Developed by:vutukuri sai kumar Reddy
#RegisterNumber:212224230307
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
result=np.linalg,solve(a,b)
print(result)
```

## Output:
![Screenshot 2025-03-21 113410-1](https://github.com/user-attachments/assets/f8891bfd-2661-4767-8ceb-976526f0a06c)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

