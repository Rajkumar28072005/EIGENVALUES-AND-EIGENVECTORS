# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
start the program
### Step 2: 
Enter the values
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Stop the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rajkumar G
#RegisterNumber:23003498
import numpy as np
a = np.array([[2,2],[1,3]])
values,vector = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vector))
```
## Output:
![Screenshot 2023-12-29 110013](https://github.com/Rajkumar28072005/EIGENVALUES-AND-EIGENVECTORS/assets/144980101/cc0e381b-2029-4a36-b774-f16ffbf7b688)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
