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

## The 1-norm of a matrix 
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## The L2 norm (or Euclidean norm) 
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## The infinity norm of a matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```







## Output:
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/67144b71-9b10-4253-935e-9786a0e26a7c" />
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/eebdb4f6-13c7-4859-b077-4b1be0a419ef" />
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/13eb4199-6136-4b9f-b92e-95e5359e4971" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
