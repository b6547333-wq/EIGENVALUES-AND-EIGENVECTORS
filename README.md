# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import the NumPy library and define the matrix.
### Step 2: Use the function np.linalg.eig() to compute the eigenvalues and eigenvectors.
### Step 3:  Store the obtained eigenvalues and eigenvectors in separate variables.
### Step 4:  Display the eigenvalues and eigenvectors.


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: J MOhamed Arsath
#RegisterNumber:212225040237
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

# Given matrix
A = np.array([[-2,  2, -3],
              [ 2,  1, -6],
              [-1, -2,  0]])

# Finding eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues,
      "and Eigen Vectors are", eigenvectors)

```

## Output:
<img width="1297" height="822" alt="image" src="https://github.com/user-attachments/assets/e25b5d8c-2e6d-494b-9a4c-75bea4922d53" />
<img width="1304" height="354" alt="image" src="https://github.com/user-attachments/assets/82fb4942-bfa8-477c-87bd-edb1890d8f4d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
