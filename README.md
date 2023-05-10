# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
	
## Algorithm:

### Step1 :

Import the numpy module to use the built-in functions for calculations. 

### Step 2:

Prepare the lists from each equations and assign in np.array()

### Step 3:

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

end the program

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: PREM KUMAR K 
#RegisterNumber: 212222230111
import numpy as np
A=np.array([[4,2],[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)

    ```
## Output:

[4th exp mathh](https://github.com/premkumarkarthikeyan/EIGENVALUES-AND-EIGENVECTORS/assets/119476243/2603d56e-2bc3-4840-9efb-0baba8062d85)


## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
