# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the inverse of the matrix and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix
### Step 4: 
End the program

## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: Dharani.E
#RegisterNumber: 21500555
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
value=np.linalg.inv(A)
print(value)
~~~
## Output:
![output](./daa.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

