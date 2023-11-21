# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in functions for caluculation
### Step 2: 
Get the input matrix from the user

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program


## Program:                                                                                                                                                                                     ```  

#Program to find the eigen values and eigen vectors.
#Developed by:L.yagnesh kumar reddy 
#RegisterNumber:23004742
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)

```
## Output:                                                                                                                                                                                        ![image](https://github.com/23004742/EIGENVALUES-AND-EIGENVECTORS/assets/150319318/dac797b2-53c9-4f66-9096-7da50ff0f24c)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
