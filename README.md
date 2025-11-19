# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy module as np
### Step 2: Define the matrix as numpy array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the result using print() function

## Program:
```
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1920" height="1080" alt="Screenshot (121)" src="https://github.com/user-attachments/assets/c0a60239-7b5e-4e18-82c2-44c9251c0a00" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
