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
Developed by: kushali p g
RegisterNumber: 23012804
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
Developed by:kushali p g
RegisterNumber: 23012804
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
![image](https://github.com/KUSHALI104/LU-Decomposition/assets/150231135/f1cdb394-5b85-4e7b-8ebd-651be209f135)
![image](https://github.com/KUSHALI104/LU-Decomposition/assets/150231135/69985840-fc5d-4a81-9304-51472b9f9d67)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

