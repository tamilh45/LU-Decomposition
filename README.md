# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Import the necessary libraries: numpy and lu function from scipy.linalg.
### Step 2:
Define the matrix A using np.array() with given elements.
### Step 3:
Perform LU decomposition using lu(A) to get matrices P, L, and U.
### Step 4:
Display the matrices L, and U using print().
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Tamil Pavalan M
RegisterNumber: 212223110058
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
Developed by: Tamil Pavalan M
RegisterNumber: 212223110058
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
# (i) To find the L and U matrix
![image](https://github.com/user-attachments/assets/f871f67b-2a7c-402f-8d3d-99cc0b66485c)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/user-attachments/assets/8c1c0069-3803-4b7c-811e-cb11c24dc885)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

