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
~~~
#Program to find the solution for the given linear equations.
#Developed by: Guhan.K
#RegisterNumber:25014479
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
x=np.linalg.solve(a,b)
print(x)
~~~
## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7f1cec07-23b6-451c-b387-62c10eaa497c" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

