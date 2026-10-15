# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Importing the Numpy module as np
### Step 2: Creating the given matrix using the np.array() function
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Printing the Eigenvalues and Eigenvectors using f"string

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sre Vishnu Priyar L N
#RegisterNumber: 26009605
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print(F"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1342" height="952" alt="image" src="https://github.com/user-attachments/assets/98cb94f1-35e6-4c5f-8d1c-a6f0f4422c12" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
