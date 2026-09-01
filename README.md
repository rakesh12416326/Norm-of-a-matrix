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
<img width="1207" height="772" alt="image" src="https://github.com/user-attachments/assets/c631f7aa-3999-4385-9519-0d684ae2649a" />
<img width="927" height="768" alt="image" src="https://github.com/user-attachments/assets/437d2e38-b8d4-4b3a-9364-9033c8c16d02" />
<img width="1082" height="770" alt="image" src="https://github.com/user-attachments/assets/f42db384-fedc-45ab-964c-5c55710ede67" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
