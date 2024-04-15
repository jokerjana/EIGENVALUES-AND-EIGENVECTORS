# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: JANARTHANAN B
#RegisterNumber:212223100014
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigvalues, eigvectors =np.linalg.eig(matrix)
print("Eigen values are", eigvalues, "and Eigen Vectors are", eigvectors) 

## Output:
![image](https://github.com/jokerjana/EIGENVALUES-AND-EIGENVECTORS/assets/147173630/2846f47c-1072-4862-911a-c1efcb6bcad4)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
