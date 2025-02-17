# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: TILAK VELLACHI
RegisterNumber: 23009564
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: TILAK VELLACHI
RegisterNumber: 23009564
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![image](https://github.com/Thilak45/LU-Decomposition/assets/138849161/9f989639-0416-4535-821d-9439cfcea8f6)
![image](https://github.com/Thilak45/LU-Decomposition/assets/138849161/a7ced794-f50d-4b5e-af76-af8810b84b4e)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

