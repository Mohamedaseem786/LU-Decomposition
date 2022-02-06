# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. start
2. Import numpy library using import statement. 
3. Import scipy library using import statement.
4. Get input from user 
5. print values
6. end


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:mohan raj
RegisterNumber: 21500140
*/
import numpy as np
import scipy
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:mohan raj
RegisterNumber:21500140
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv= lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)

```

## Output:
![lu decomposition](1.png)
![lu decomposition](2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

