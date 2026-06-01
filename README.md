# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program and import the required library (numpy).
2. Initialize the matrix for which the LU decomposition needs to be found.
3. Apply LU Decomposition
4.Display the results

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:   VARSHA M
RegisterNumber: 212225230291
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U = lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: VARSHA M
RegisterNumber: 212225230291
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,pivot = lu_factor(a)
x = lu_solve((lu,pivot),b)
print(x)
*/
```

## Output:
<img width="1317" height="856" alt="image" src="https://github.com/user-attachments/assets/d6f94a47-e0f7-455b-83f1-b958a6f0d2da" />
<img width="1288" height="776" alt="image" src="https://github.com/user-attachments/assets/c605d1e9-dcd3-4594-b541-a8a9dadfdbf2" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

