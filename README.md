# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : To find inverse of a matrix using python programming.
### Step 2: Import numpy as np.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:  Print result.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: yuvabharathib
#RegisterNumber:22002787
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot (3)](https://user-images.githubusercontent.com/113497404/192129626-fd0c5a59-f915-48f8-b012-c32625064956.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
