# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Import numpy library using import statement
From scipy package import lu()
Get input from user and pass it as an array
Get P,LU matrix using lu()
Print L and U matrix
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S.Meena
RegisterNumber: 21500895
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S.Meena
RegisterNumber: 21500895
import numpy as np
import scipy
from scipy.linalg import lu
A =eval(input())
P,L,U=lu(A)
print(L)
print(U)
*/


Program to find the LU Decomposition of a matrix.
Developed by: S.Meena
RegisterNumber:21500895
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv= lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)
*/

```

## Output:
![lu decomposition](./sso.png)
![lu decomposition](./ssp.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

