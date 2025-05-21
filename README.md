# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
Import the numpy module to use the built-in functions for calculation
## Step 2:
Prepare the lists from each linear equations and assign in np.array()
## Step 3:
Using the np.linalg.solve(), we can find the solutions.
## Step 4: 
End the program


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SAVISH R
#RegisterNumber:212224230257

import numpy as np
matrix = np.array([[2, 2],[1, 3]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

```


## Output:
![image](https://github.com/user-attachments/assets/47049cd0-f502-42e1-b50e-94ec3ccd82aa)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
