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
```Python
# Register No:22008369
# Developed By: NIRAUNJANA GAYATHRI G R

# 1-Norm of a Matrix:

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix:

Program to find 2-norm of a matrix.
Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber: 22008369
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix:

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-16%2017-18-14.png![image](https://user-images.githubusercontent.com/119395610/212671978-65b4d6b6-2924-4ebb-a989-373740b937f4.png)


### 2-Norm of a Matrix
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-16%2017-19-18.png![image](https://user-images.githubusercontent.com/119395610/212672055-1b72b4b9-e5fc-4df0-8989-5c747308d3b2.png)


### Infinity Norm of a Matrix

file:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-16%2017-20-00.png![image](https://user-images.githubusercontent.com/119395610/212672131-b6ef313c-ed3b-469c-aa75-159aa042ec3d.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
