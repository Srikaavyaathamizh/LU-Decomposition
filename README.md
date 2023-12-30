# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using import statement 
2. from scipy package import lu()
3. get input from user and pass it as an array
4. get P,LU matrix using lu()
5. print L and U matrix
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SRIKAAVYAA T
RegisterNumber: 23013589

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SRIKAAVYAA T
RegisterNumber: 23013589

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
l=lu_solve((lu,piv),b)
print(l)
*/
```

## Output:
![Alt text](<Screenshot 2023-12-30 173110.png>)
![Alt text](<Screenshot 2023-12-30 173143.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

