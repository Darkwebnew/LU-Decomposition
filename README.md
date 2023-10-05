# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L, U matrix using lu()
5. Print L and U matrix

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Sriram.V
RegisterNumber: 23013561
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![Screenshot 2023-10-05 202232](https://github.com/Darkwebnew/LU-Decomposition/assets/143114486/45d52fa3-1b8d-431e-b16f-c1bf2fef51e7)

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scipy package import lu_factor() and lu_solve().
3. Get two inputs from user and pass it as matrix array.
4. Find lu and pivot value of first matrix using lu_factor().
5. Find solution of the matrix by using lu_solve() by passing lu, pivot values as first argument and second matrix as second argument.
6. Print the solution.

## Program:
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Sriram.V
RegisterNumber: 23013561
'''
import numpy as np
from scipy.linalg import lu_factor ,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv,),b)
print(x)
```

## Output:
![Screenshot 2023-10-05 202232](https://github.com/Darkwebnew/LU-Decomposition/assets/143114486/45d52fa3-1b8d-431e-b16f-c1bf2fef51e7)
![Screenshot 2023-10-05 202305](https://github.com/Darkwebnew/LU-Decomposition/assets/143114486/dacd7c22-69dc-49d3-8b55-97aa9b32b158)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

