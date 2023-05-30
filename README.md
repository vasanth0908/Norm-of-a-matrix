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
# '''
Program to find 1-norm of a matrix.
Developed by: s.vasanth
RegisterNumber: 212222110052
'''
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: s.vasanth
RegisterNumber: 212222110052
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: s.vasanth
RegisterNumber: 212222110052
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))





```
## Output:
### 1-Norm of a Matrix
![16](https://github.com/vasanth0908/Norm-of-a-matrix/assets/122000018/cd6945fa-b61a-429b-91c2-785de1ee7a11)

<br>
<br>
<br>

### 2-Norm of a Matrix
![17](https://github.com/vasanth0908/Norm-of-a-matrix/assets/122000018/bae9d16b-2a58-459a-9179-c920c04c3b30)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![18](https://github.com/vasanth0908/Norm-of-a-matrix/assets/122000018/48c3d558-da61-434e-8473-bd2e95bcd5d1)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
