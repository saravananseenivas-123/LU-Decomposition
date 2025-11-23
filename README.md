# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

### Step 1:
Start the program

### Step 2:
Import the necessary libraries(numpy,scipy.linalg)

### Step 3:
Define the matrix using numpy

### Step 4:
Use lu(),lu_solve(),lu_factor() to get the solutions

### Step 5:
End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S.saravanan
RegisterNumber: 25005837
*/
import numpy as np
from scipy.linalg import lu
inputmatrix = np.array(eval(input()), dtype='i')
piv, Lmatrix, Umatrix=lu(inputmatrix)
print(Lmatrix)
print(Umatrix)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S.Saravanan
RegisterNumber: 25005837
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
Amatrix=np.array(eval(input()),dtype='i')
Bmatrix=np.array(eval(input()),dtype='i')
Xmatrix=lu_factor(Amatrix)
Solution=lu_solve(Xmatrix,Bmatrix)
print(Solution)

```

## Output:
### (i) To find the L and U matrix
<img width="1106" height="804" alt="MA program #5" src="https://github.com/user-attachments/assets/0331ef9c-be3a-4cd6-8aa9-53cc0b03fd74" />
<img width="1095" height="497" alt="MA program #5 1" src="https://github.com/user-attachments/assets/b37e0a1d-0f49-43c6-8f24-4ad1473ffa2a" />

### (ii) To find the LU Decomposition of a matrix
<img width="1103" height="726" alt="MA program #5 2" src="https://github.com/user-attachments/assets/359e1a3b-fff7-48d4-b933-d77684ebb14c" />
<img width="1096" height="297" alt="MA program #5 3" src="https://github.com/user-attachments/assets/6e889a54-d0c7-4295-b6e8-1f17efc2dc7c" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

