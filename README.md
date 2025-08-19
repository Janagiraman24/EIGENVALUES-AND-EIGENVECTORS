# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End of program
## Program:
# Program to find the eigen values and eigen vectors.
# Developed by: Janagiraman.M 
# RegisterNumber: 212224230101
```
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
<img width="1271" height="779" alt="Screenshot 2025-08-19 184949" src="https://github.com/user-attachments/assets/7782c20c-f939-4ddb-8ae1-e364121fec5c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
