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
#Developed by: Dhandeeswaran selvakumar
#RegisterNumber:23006838
import numpy as np
a = np.array([[2,2],[1,3]])
values,vector = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vector))
```
## Output:
![output](https://github.com/dhandeeswaran2005/EIGENVALUES-AND-EIGENVECTORS/assets/147139188/6e2b2b43-7bf3-440b-b2c7-195cabefc840)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
