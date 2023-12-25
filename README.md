# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

## i)
## Step1:
Prompt the user to enter a matrix and covert the input to a numpy array.
## Step2:
Use the LU decomposition function(LU) on the input matrix.
## Step3:
Retrieve the permutation matrix(P) lower triangular matrix(L), upper triangular matrix(U).
## Step4:
Display the lower triangular matrix (L) and upper triangular matrix(U).

## ii) 
## Step1:
Convert the input to numpy arrays (A and B)
## Step2:
Use the lu_factor function to complete the LU factorization of matrix A.Get a factorization result (result) that  is needed for solving linear systems.
## Step3:
Apply the lu_solve function using the LU factorization result (result) and the constant vector B.
## Step4:
Obtain the solution to a linear solution and display the solution to the linear solution.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: P.Sasinthar
RegisterNumber: 23012532

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: P.Sasinthar
RegisterNumber: 23012532

from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
*/
```

## Output:
![Screenshot 2023-12-25 173256](https://github.com/sasintharparanthaman/LU-Decomposition/assets/145743219/72ac43ef-522e-468e-9184-84a5cb8da180)

![Screenshot 2023-12-25 173306](https://github.com/sasintharparanthaman/LU-Decomposition/assets/145743219/f3057552-32f4-44bc-bd52-8780996cb7fa)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

