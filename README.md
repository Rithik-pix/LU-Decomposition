# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array().
3. Using the scipy.linalg and imort lu_fator and lu_solve we get the values.
4. End the program

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.

Developed by: S.Rithik Ram

RegisterNumber: 24004502

import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.

Developed by: S.Rithik Ram 

RegisterNumber: 24004502

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```
## Output:
![Screenshot 2024-12-12 143856](https://github.com/user-attachments/assets/976696bd-5088-4121-bdf2-12460b536237)
![Screenshot 2024-12-12 143913](https://github.com/user-attachments/assets/9b31a2d6-f30c-426d-a380-a77a8a262836)









## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

