# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: Import the required NumPy library.
### Step 2: Define the matrix A.
### Step 3: Use numpy.linalg.eig() to find the eigenvalues and eigenvectors of the matrix.
### Step 4: Print the eigenvalues and eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Lohith v
#RegisterNumber:212225230154

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

a = np.array([[-2, 2, -3], [2, 1, -6], [-1, -2, 0]])

values, vectors = np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values, vectors))
```
## Output:
![alt text](<Screenshot 2026-06-03 130908.png>)

![alt text](<Screenshot 2026-06-03 130926.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
