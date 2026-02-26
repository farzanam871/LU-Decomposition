# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program
   

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Farzana M
RegisterNumber: 212225040087
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
Developed by: Farzana M
RegisterNumber: 212225040087
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
*/
```

## Output:
<img width="1304" height="976" alt="Screenshot 2026-02-26 140243" src="https://github.com/user-attachments/assets/3542ab7c-fa3d-49b1-ac6a-06bac8ec97d6" />

<img width="1232" height="919" alt="Screenshot 2026-02-26 140321" src="https://github.com/user-attachments/assets/0c85c01d-76f7-4f55-9af6-f800d4b87581" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

