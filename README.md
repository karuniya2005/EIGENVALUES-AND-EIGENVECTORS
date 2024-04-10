# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2:  store the variable in a variable using np.array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the respected eigen value and eigen vector

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:KARUNIYA M 
#RegisterNumber:212223240068
import numpy as np
matrix = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```
## Output:
![Screenshot 2024-04-10 202136](https://github.com/karuniya2005/EIGENVALUES-AND-EIGENVECTORS/assets/161425769/15d3c627-7dac-410f-b988-7d9f7beb9006)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
