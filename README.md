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
# Register No:212225040161 (25017654)
# Developed By:Joshua Daniel A
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:




### 1-Norm of a Matrix
<br><img width="1234" height="239" alt="Screenshot 2026-02-07 085410" src="https://github.com/user-attachments/assets/efd003aa-a1b5-47d2-bae4-2313aeab3151" />
<br>
<br>

### 2-Norm of a Matrix
<br><img width="1221" height="279" alt="Screenshot 2026-02-07 085424" src="https://github.com/user-attachments/assets/f86f816c-4021-4b0f-b094-861b025f564f" />
<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1235" height="245" alt="Screenshot 2026-02-07 085438" src="https://github.com/user-attachments/assets/5490d198-0ec7-4a5c-a735-686fe1499403" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
