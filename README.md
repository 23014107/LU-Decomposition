# LU Decomposition 
NAME:RAMYA.P
REG NO:212223240137
DEPT:AIML

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy extention and scipy.linalg extension
2. Initialize the matrix values
3. Use lu functions from imported extension
4. Print the output

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: RAMYA.P
RegisterNumber: 212223240137
*/
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: RAMYA.P
RegisterNumber: 212223240137
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

## Output:
![lu decomposition]()
![Screenshot 2024-04-22 203331](https://github.com/23014107/LU-Decomposition/assets/151625620/79073fc0-e68a-4570-bfad-9197140b1ecb)
![Screenshot 2024-04-22 203459](https://github.com/23014107/LU-Decomposition/assets/151625620/5aff407c-fa85-43b2-a3be-93d0015489e7)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

