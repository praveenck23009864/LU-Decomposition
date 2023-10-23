# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. First,we want to import nump
2. Then we want import scipy.linalg and import lu for lu decomposition
3. Then we want to assume a input
4. Then print a result.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: praveen ck
RegisterNumber: 23009864
*/
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: praveen ck
RegisterNumber: 23009864
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/praveenck23009864/LU-Decomposition/assets/141472050/d25109ff-60ad-4e25-870b-14a2f775d9af)

![Screenshot 2023-10-23 214046](https://github.com/praveenck23009864/LU-Decomposition/assets/141472050/606b405a-c4da-471a-991e-2b47306b323a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

