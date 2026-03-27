# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm


(i).Algorithm for Program 1 (Finding L and U matrices)

1.Start the program.

2.Import necessary libraries (numpy, scipy.linalg).

3.Read the input matrix A.

4.Apply LU decomposition using lu(A) which returns permutation matrix P, lower triangular matrix L, and upper triangular matrix U.

5.Print the L matrix.

6.Print the U matrix.

7.End the program.




(ii).Algorithm for Program 2 (Solving system of equations using LU decomposition)

1.Start the program.

2.Import necessary libraries (numpy, scipy.linalg).

3.Read the coefficient matrix a.

4.Read the constant matrix/vector b.

5.Perform LU factorization using lu_factor(a) which returns LU decomposition and pivot indices.

6.Solve the system using lu_solve((lu, piv), b) to get solution vector x.

7.Print the solution (x).

8.End the program.




## Program:
(i) To find the L and U matrix

```python 
/*
Program to find the L and U matrix.
Developed by: ALLEN PRAKASH J
RegisterNumber: 25011975
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix

```python
/*
Program to find the LU Decomposition of a matrix.
Developed by:ALLEN PRAKASH J 
RegisterNumber: 25011975
*/

a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```


## Output:


<img width="1255" height="590" alt="Screenshot 2026-02-12 170957" src="https://github.com/user-attachments/assets/5183f137-bc7f-4bc3-abd4-8c6710df160d" />









<img width="1272" height="362" alt="Screenshot 2026-02-12 171908" src="https://github.com/user-attachments/assets/d3748794-7eb3-465e-816b-4ba739ab0eb7" />







## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

