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
```python

#Program to find the solution for the given linear equations.
#Developed by: S.Roselin mary jovita
#RegisterNumber:212222230122
import numpy as no
A=no.array([[1,-3],[3,1]])
B=no.array([0,10])
result=no.linalg.solve(A,B)
print(result)
```




## Output:

![linear](https://user-images.githubusercontent.com/119104296/225912697-185d5501-fa8e-4aae-8761-8bb8c638dd74.png)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

