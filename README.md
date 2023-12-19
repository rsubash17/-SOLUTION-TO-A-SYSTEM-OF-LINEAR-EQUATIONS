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
#Developed by: SUBASH R
#RegisterNumber:23003821
import numpy as np
A= np.array([[1,-3],[3,1]])
B=np.array([0,10])
lin=np.linalg.solve(A,B)
print(lin)

```
## Output:
![Screenshot 2023-11-09 025548](https://github.com/rsubash17/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/147139828/c0c1a960-44d2-4d62-9f3b-42bb19be7dfe)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program
Thus the solutions for the linear equations are successfully solved using python program

