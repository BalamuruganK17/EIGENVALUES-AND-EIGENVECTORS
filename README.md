# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : First import numpy as np
### Step 2: Declare A for the array of elements
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Finally print the Eigen values and Eigen vectors

## Program:
```

#Program to find the eigen values and eigen vectors.
#Developed by: BALAMURUGAN.K
#RegisterNumber: 25017932

import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

```
Screenshot:
<img width="1498" height="692" alt="Screenshot 2025-11-22 151957" src="https://github.com/user-attachments/assets/66aa512f-60a5-4a46-bc1e-451be75b9a79" />


## Output:
<img width="1497" height="282" alt="Screenshot 2025-11-22 152027" src="https://github.com/user-attachments/assets/490ca660-51d2-4762-8cd1-47639e033391" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
