# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the necessary modules: NumPy for array creation and scipy.linalg for LU functions.
2. Define a square matrix using np.array().
3. Use scipy.linalg.lu() to decompose the matrix into L (Lower), U (Upper), and P (Permutation) matrices.
4. Display the matrices P, L, and U using print statements.
5. End the program.
## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: abheek.a
RegisterNumber: 212224100001
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: abheek
RegisterNumber: 212224100001
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```
## Output:
![Screenshot 2025-04-25 152536](https://github.com/user-attachments/assets/a6d396d8-3649-473b-8460-8d587d216dab)
![Screenshot 2025-04-25 152552](https://github.com/user-attachments/assets/1c60200f-e4c9-4068-b0a6-f7ec30585295)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

