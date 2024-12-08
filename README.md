# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: Import the numpy module to use the built-in function for calculation
### Step 2: Prepare from scipy.linalg import lu and assign in np.array()
### Step 3: Using lu(), we can find the L and U of the given matrix.
### Step 4: End the program 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: PRIYADHARSHINI G
RegisterNumber: 24900479'''

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U =  lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: PRIYADHARSHINI G
RegisterNumber: 24900479
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu , piv = lu_factor(A)
x= lu_solve((lu,piv),b)
print(x)
```

## Output:
![alt text](<Screenshot 2024-12-08 135129.png>)
![alt text](<Screenshot 2024-12-08 135038.png>)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

