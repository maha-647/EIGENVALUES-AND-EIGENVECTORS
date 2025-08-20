# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Mahalaksshmi Mridula
#RegisterNumber: 212224220056
import numpy as np
A = np.array([[-2, 2, -3], [2, 1, -6], [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)

```

## Output:
<img width="1496" height="909" alt="image" src="https://github.com/user-attachments/assets/2cfa4c45-119c-4d9a-972d-03f1b0c68353" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
