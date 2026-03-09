# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Write a python program for the given matrix
### Step 2: Using numpy library
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Run the program and get the output

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: IRFANA M
#RegisterNumber: 212225230105

import numpy as np
matrix = np.array([[4,2],[2,4]])
eig_values,eig_vectors = np.linalg.eig(matrix)
print(f"Eigen values are {eig_values} and Eigen Vectors are {eig_vectors}")

## Output:
<img width="1354" height="824" alt="Screenshot 2026-02-10 113613" src="https://github.com/user-attachments/assets/29aa49a5-1ee3-48fb-9a71-07cd923024dc" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
