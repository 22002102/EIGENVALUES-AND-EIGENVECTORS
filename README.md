# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Import numpy as np.


Step 2:
Initialize the matrix using np.array()


Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.


Step 4:
Print the output.

## Program:
```
Developed by: SANJAY S
RegisterNumber:212222230132
import  numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:

![image](https://github.com/22002102/EIGENVALUES-AND-EIGENVECTORS/assets/119091638/5ed1b43c-60d0-474a-9abe-a10b53278f51)




## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
