# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Input the Matrix
2. Perform LU Decomposition
3. Extract Factors
4. Display Results

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ALLEN PRAKASH J
RegisterNumber: 25011975
*/
```python
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
Developed by:ALLEN PRAKASH J 
RegisterNumber: 25011975
*/
```python
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:


<img width="1255" height="590" alt="Screenshot 2026-02-12 170957" src="https://github.com/user-attachments/assets/5183f137-bc7f-4bc3-abd4-8c6710df160d" />


<img width="898" height="562" alt="Screenshot 2026-02-12 170749" src="https://github.com/user-attachments/assets/b4e4d922-ec42-4965-8bdc-6843fe62f243" />






## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

