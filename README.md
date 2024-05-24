# EX-5: LU Decomposition 
### DATE: 30.03.24
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X'
include the package in that variable.
4.Print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Mohankumar S 
RegisterNumber: 2305002014
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Mohankumar S 
RegisterNumber: 2305002014
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![image](https://github.com/MohanKumar755/LU-Decomposition/assets/146155007/772db2f4-724f-43af-b385-540283d8a6e2)

![image](https://github.com/MohanKumar755/LU-Decomposition/assets/146155007/58532d93-45ed-4325-bbf0-b935d2201267)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

