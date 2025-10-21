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
# Register No: 25003780
# Developed By: Thenamizhthan V
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_matrix = "{:.2f}".format(ans)
print(norm_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_matrix = "{:.2f}".format(ans)
print(norm_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1230" height="341" alt="(i)" src="https://github.com/user-attachments/assets/cb4d1169-74f3-4ec5-959f-07c618f0c420" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1231" height="402" alt="(ii) (2)" src="https://github.com/user-attachments/assets/8a0cf7a3-639f-41a8-88c0-c7642c5fdb06" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1241" height="347" alt="(iii) (2)" src="https://github.com/user-attachments/assets/c2480139-9b6c-4d42-8a77-b4e65a8cc047" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
