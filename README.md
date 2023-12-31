# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np 
2. Include "from scipy.linalg import lu" for 1st experiment  
3. Include "from scipy.linalg import lu_factor , lu_solve"for the 2nd experiment
4. Print the output
5. End the program

## Program:
## (i) To find the L and U matrix
### Program to find the L and U matrix.
### Developed by: JOTHIKRISHNAA V
### RegisterNumber: 212223100017
~~~
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
~~~

## (ii) To find the LU Decomposition of a matrix
### Program to find the L and U matrix.
### Developed by: JOTHIKRISHNAA V
### RegisterNumber: 212223100017
~~~
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
~~~
## Output:
(i) To find the L and U matrix
![lu matrix](<Screenshot 2023-12-31 135839.png>)
(ii) To find the LU Decomposition of a matrix
![LU Decomposition](<Screenshot 2023-12-31 135854.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

