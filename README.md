# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
use the module numpy as np as follows
### Step 2:
use function np.array to create the matrix
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
output has been excueted and give print to see the output

## Program:
```
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2023-12-19 144534](https://github.com/franklinraj/EIGENVALUES-AND-EIGENVECTORS/assets/148993740/adcd49c7-2745-4ca0-8b3a-368b77582ccf)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
