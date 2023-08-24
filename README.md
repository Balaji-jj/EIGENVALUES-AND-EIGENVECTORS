# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2:
get input from the user using array
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
now print the eigen values and eigen vector

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Balaji J
#RegisterNumber:212221243001
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
x,y=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(x,y))
```
## Output:
![image](https://github.com/Balaji-jj/EIGENVALUES-AND-EIGENVECTORS/assets/142155013/c8818ba6-55c3-4169-8401-c7be9a34381a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
