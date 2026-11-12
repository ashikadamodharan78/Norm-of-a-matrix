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
# Register No: 26009780
# Developed By: Ashika D
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))





```
## Output:
### 1-Norm of a Matrix
<img width="1448" height="859" alt="Screenshot 2026-11-12 202139" src="https://github.com/user-attachments/assets/b6569679-9624-475b-b88f-1787dcb6ec65" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1435" height="872" alt="{7500CC3C-1026-4FF2-B340-47DA5B861DDE}" src="https://github.com/user-attachments/assets/1a6dac2a-0cba-4dd3-8eef-41e07ab8c4d7" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="1450" height="829" alt="Screenshot 2026-11-12 202355" src="https://github.com/user-attachments/assets/ddd82975-f088-45d4-b021-27115d7cc508" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
