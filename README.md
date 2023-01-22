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
![WhatsApp Image 2023-01-22 at 17 23 31](https://user-images.githubusercontent.com/119395610/213914445-f1a99fa8-26a0-4271-89d8-4aefc66459aa.jpg)
![WhatsApp Image 2023-01-22 at 17 23 41](https://user-images.githubusercontent.com/119395610/213914451-ea41add0-bc0d-4697-ab80-adf3cc24565d.jpg)
![WhatsApp Image 2023-01-22 at 17 23 50](https://user-images.githubusercontent.com/119395610/213914460-966e8e66-436e-457e-9716-527658bdff73.jpg)
![WhatsApp Image 2023-01-22 at 17 24 00](https://user-images.githubusercontent.com/119395610/213914472-fee30660-6644-4f8e-861c-de3852ce5cd7.jpg)
![WhatsApp Image 2023-01-22 at 17 24 10](https://user-images.githubusercontent.com/119395610/213914477-fdb677e7-79e5-435b-83b6-a27d7fb49ac8.jpg)
![WhatsApp Image 2023-01-22 at 17 24 20](https://user-images.githubusercontent.com/119395610/213914487-a1734cd0-6356-4042-8449-4db805ea64c1.jpg)



### 2-Norm of a Matrix
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-16%2017-19-18.png![image](https://user-images.githubusercontent.com/119395610/212672055-1b72b4b9-e5fc-4df0-8989-5c747308d3b2.png)


### Infinity Norm of a Matrix

file:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-16%2017-20-00.png![image](https://user-images.githubusercontent.com/119395610/212672131-b6ef313c-ed3b-469c-aa75-159aa042ec3d.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
