# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Start
Step 2: Input the matrix
Take the given square matrix 
𝐴
A.

Step 3: Find the eigenvalues
Solve the characteristic equation:

det
(
𝐴
−
𝜆
𝐼
)
=
0
det(A−λI)=0
where:

𝜆
λ is an eigenvalue,

𝐼
I is the identity matrix of the same size as 
𝐴
A,

det
det means the determinant.

Solve for 
𝜆
λ (you may get one or more eigenvalues).

Step 4: Find the eigenvectors
For each eigenvalue 
𝜆
λ:

Substitute 
𝜆
λ into the equation:

(
𝐴
−
𝜆
𝐼
)
𝑋
=
0
(A−λI)X=0
Solve this system to find the corresponding eigenvector 
𝑋
X.

Step 5: Output the eigenvalues and eigenvectors
Step 6: End

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:SAVISH R 
#RegisterNumber:212224230257
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))



## Output:
![image](https://github.com/user-attachments/assets/47049cd0-f502-42e1-b50e-94ec3ccd82aa)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
