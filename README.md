# 2-Norm of a matrix
## AIM:
To write a program to find the 2-norm of the matrix and display the result in two decimal places.

## EQUIPMENT'S REQUIRED:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM:
	1. Get the input matrix using np.array()
	2. The 2-Norm of a matrix is given by 
![norm](./normeqn1.jpg)
    
    3. Find the 2-norm of the matrix using np.linalg.norm()
	4. Print the norm of the matrix in two decimal places.

## PROGRAM:
```
Program to find 2-norm of a matrix.
Developed by: Aashima Nazreen Sayeed S
RegisterNumber: 21500368

import numpy as np
n = eval(input())
val = np.linalg.norm(n,2)
print("{:.2f}".format(val))
```

## SAMPLE INPUT AND OUTPUT: 

### Input:
![norm1](./input.jpg)

### Output:
![output](./output1.png)

## RESULT: 
Thus the program for 2-norm of a matrix is written and verified.
