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
```
#Register No: 23011002
#Developed By: guntur shaik mohammad shahil
#1-Norm of Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/mohammadshahil09/Norm-of-a-matrix/assets/145742840/2a10be0a-e9c3-4c41-8ae1-fcfe98714c2f)


### 2-Norm of a Matrix
![image](https://github.com/mohammadshahil09/Norm-of-a-matrix/assets/145742840/a31ade60-a7ae-48cc-a5f4-f0c79133a991)


### Infinity Norm of a Matrix
![image](https://github.com/mohammadshahil09/Norm-of-a-matrix/assets/145742840/bb9ecf76-a494-4771-908c-b6495d75fbc8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
