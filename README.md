# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)
```

## Output:
![lu decomposition]()
![Screenshot 2024-12-01 195731](https://github.com/user-attachments/assets/efbb99d4-fdce-4d7e-8256-ac2918b8d142)
![Screenshot 2024-12-01 195744](https://github.com/user-attachments/assets/e08449c9-3467-4400-96ee-ad8e4939ee1f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

