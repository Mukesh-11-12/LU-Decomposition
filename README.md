# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu
2. Get input from and print 'L' and 'U' matrix by 'Print'
3. Define a package as "from scipy.linalg import lu_factor,lu_solve"and create the variable as 'X' include the package in that variable
5. print the variablr 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```
## Output:
![lu decomposition]()

<img width="1480" height="975" alt="Screenshot 2025-08-28 093052" src="https://github.com/user-attachments/assets/d7790a46-301b-47e0-b60e-ccb1822175ad" />

<img width="1489" height="882" alt="Screenshot 2025-08-28 093108" src="https://github.com/user-attachments/assets/f82aee5f-29f0-478d-ade8-82fd295cf4aa" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

