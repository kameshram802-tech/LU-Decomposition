# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
~~~
1: Import the required library (SciPy or similar library that supports LU decomposition).
2:Define the square matrix.
3:Apply the LU decomposition function to the matrix to obtain L and U (and P if required).
4: Display the matrices L and U (and P, if used).
~~~
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Kamesh A
RegisterNumber: 212225230123
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
Developed by: Kamesh A
RegisterNumber: 212225230123
*/
import numpy as np
from scipy.linalg import lu factor, lu solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot= lu factor(A)
x=lu solve((lu,pivot),B)
print(x)
```

## Output:
(i)
<img width="1273" height="818" alt="Screenshot 2026-02-12 082858" src="https://github.com/user-attachments/assets/5b3be21b-3a16-4eb2-bd13-fb900d82e141" />
(ii)

<img width="1295" height="741" alt="Screenshot 2026-02-12 082929" src="https://github.com/user-attachments/assets/1593b06d-fd3b-4e80-8359-4d5d9f628368" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

