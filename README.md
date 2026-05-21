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
# Register No: 212225240146
# Developed By: Shrivarshan
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)









```
## Output:
### 1-Norm of a Matrix
<img width="1020" height="803" alt="Screenshot 2026-05-21 101914" src="https://github.com/user-attachments/assets/fbdb679e-4400-42ec-9076-42bc6590ff9e" />


### 2-Norm of a Matrix
<img width="852" height="802" alt="Screenshot 2026-05-21 101929" src="https://github.com/user-attachments/assets/c08fa95a-867d-4302-9d11-624b9d939e05" />


### Infinity Norm of a Matrix

<img width="736" height="773" alt="Screenshot 2026-05-21 101944" src="https://github.com/user-attachments/assets/bebf7a72-861f-4e85-859b-098a4c2d4bba" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
