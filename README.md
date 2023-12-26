# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import libraries
2. get the matrix from the user
3. find the L and U
4. print the solution

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Roshini.S
RegisterNumber: 23008859
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
Program to find the L and U matrix.
Developed by:Roshini.S 
RegisterNumber: 23008859
*/
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Roshini.S
RegisterNumber: 23008859
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
con=eval(input())
A=np.array(arr)
B=np.array(con)
result=lu_factor(A)
sol=lu_solve(result,B)
print(sol)
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:
![lu decomposition]()
![image](https://github.com/23008859/LU-Decomposition/assets/139117979/a6ac723d-0fac-4453-bca5-5448d03ebaac)
![image](https://github.com/23008859/LU-Decomposition/assets/139117979/ebecece3-2c91-4843-be5d-9af3951f211f)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

