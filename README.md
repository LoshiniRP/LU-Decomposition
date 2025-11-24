## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the necessary libraries(numpy,scipy.linalg) to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the lu(), lu_solve(), lu_factor(), we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
p, l, u = lu(a)
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
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu, pivot = lu_factor(a)
x = lu_solve((lu, pivot), b)
print(x)
```

## Output:
<img width="1205" height="344" alt="Screenshot 2025-11-24 184246" src="https://github.com/user-attachments/assets/4176932c-caf9-4177-b538-1cbba95fa2c0" />

<img width="1203" height="342" alt="Screenshot 2025-11-24 184318" src="https://github.com/user-attachments/assets/b19857d5-d1f6-42da-a537-a7a206082345" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
