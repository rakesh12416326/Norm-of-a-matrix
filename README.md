# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:

# Register No:212225240114
# Developed By: rakesh s

## The 1-norm of a matrix (often called the maximum column sum norm) is calculated as the ## maximum sum of the absolute values of the elements in each column. 

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


## #The L2 norm (or Euclidean norm) of a vector measures the "length" or "magnitude" of the vector. Or it is the square root of sum of squares of all the elements
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

## #The infinity norm of a matrix, often called the maximum row sum norm, is defined as the #maximum sum of the absolute values of the elements in each row.

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)







```
## Output:
## 1-Norm of a Matrix
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/4f6b574a-814e-4721-ac39-485cb69ad775" />


## 2-Norm of a Matrix
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/994844a1-9f85-498f-9499-bc8677ec5fb7" />

## Infinity Norm of a Matrix
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/dd3eaaf4-6709-4261-9f9b-c23d4ef86615" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
