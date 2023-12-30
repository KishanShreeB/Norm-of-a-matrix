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
# Register No:23012867
# Developed By:Kishan Shree B
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix:
Developed by:Kishan Shree B
RegisterNumber:212223100022
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Kishan Shree B
RegisterNumber: 212223100022
'''
import numpy as np

# Type your code here

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
'''
Program to find Infinity norm of a matrix.
Developed by: Kishan Shree B
RegisterNumber:212223100022
'''

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/KishanShreeB/Norm-of-a-matrix/assets/144870434/8076ce7d-dc27-4712-afa2-655a87c7b7c1)


### 2-Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/KishanShreeB/Norm-of-a-matrix/assets/144870434/7f8ce245-61b0-429b-a1df-d13a11ad4de0)


### Infinity Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/KishanShreeB/Norm-of-a-matrix/assets/144870434/edd22604-0cb9-4a18-ae7c-c87db95c3768)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
