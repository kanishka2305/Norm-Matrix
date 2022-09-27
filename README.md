# 2-Norm of a matrix
## Aim
To write a program to find the 2-norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()
	2. The 2-Norm of a matrix is given by 
![norm](./normeqn1.jpg)
    
    3. Find the 2-norm of the matrix using np.linalg.norm()
	4. Print the norm of the matrix in two decimal places.
## Program:
```python
Program to find 2-norm of a matrix.
Developed by: kanishka.v.s
RegisterNumber: 22003409

import numpy as np
arr = np.array(eval(input()))
n = np.linalg.norm(arr,2)
r = round(n,2)
print(r)

```
Output:
![norm1](/output.png)

## Result
Thus the program for 2-norm of a matrix is written and verified.
