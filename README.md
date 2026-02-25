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
# Register No:212225040015
# Developed By:Ajithkumar .J
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
n="{:.2f}".format(ans)
print(n)




# 3. Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)






```
## Output:
### 1-Norm of a Matrix
<img width="1497" height="857" alt="{58054875-3504-42BD-BB1E-5D0115C906E2}" src="https://github.com/user-attachments/assets/8764a869-ddcd-4f29-b315-dd819668e93f" />


### 2-Norm of a Matrix
<img width="1548" height="894" alt="{060CC54C-4D44-4542-97D1-D198BE51C6AD}" src="https://github.com/user-attachments/assets/e2c53851-4b92-423a-9041-0c1deee2cff8" />


### Infinity Norm of a Matrix
<img width="1562" height="825" alt="{CDAB33BF-424D-46B5-8FD4-00B09BE2C82E}" src="https://github.com/user-attachments/assets/97505f93-3a0d-4f80-8afe-b6a5993bf546" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
