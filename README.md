# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Start
Step 2: Input the matrix
Read or write down the matrix you are given.

Step 3: Convert the matrix to Row Echelon Form (REF)
Use elementary row operations:

Swap two rows if needed.

Multiply a row by a nonzero scalar to simplify pivot elements.

Add or subtract multiples of rows to create zeros below the pivots.

Step 4: Simplify the matrix
Continue the operations until:

All the entries below every pivot (leading non-zero entry) are zeros.

Each pivot is to the right of the pivot in the row above it.

Step 5: Identify nonzero rows
A nonzero row is a row that has at least one nonzero element.

Step 6: Count the number of nonzero rows
The rank of the matrix is the number of nonzero rows.

Step 7: Output the rank
 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: SAVISH R
#RegisterNumber:212224230257

import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
![image](https://github.com/user-attachments/assets/15aedb46-d7bf-4012-883a-9a86aa8e086f)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

