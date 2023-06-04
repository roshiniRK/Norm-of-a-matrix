# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

## Step 1:

Get the input matrix using np.array()

## Step 2:

Find the 2-norm of the matrix using np.linalg.norm()

## Step 3:

Print the norm of the matrix in two decimal places.

## Program:
```Python
# Register No: 212222230123
# Developed By: ROSHINI R K
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: ROSHINI R K
RegisterNumber: 212222230123
'''
array=([[-1,3],[3,-4],[1,7]])
import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: ROSHINI R K
RegisterNumber: 212222230123
'''
array=([[-1,3],[3,-4],[1,7]])
import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix

'''
Program to find the infinity of a matrix.
Developed by: ROSHINI R K
RegisterNumber: 212222230123
'''
array=([[-1,3],[3,-4],[1,7]])
import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/roshiniRK/Norm-of-a-matrix/assets/118956165/db2909f8-a0c9-44f3-a659-d849bf1bcd0b)


### 2-Norm of a Matrix
![image](https://github.com/roshiniRK/Norm-of-a-matrix/assets/118956165/6e3b8562-7873-4de2-8500-9eb19030f0fd)


### Infinity Norm of a Matrix
![image](https://github.com/roshiniRK/Norm-of-a-matrix/assets/118956165/817b2941-0c7f-476f-818c-8a7b4630cbe6)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
