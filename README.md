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
# Register No: 25018064
# Developed By: TAMIZHAN B
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```

# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```

```
## Output:
### 1-Norm of a Matrix
![WhatsApp Image 2026-02-07 at 9 12 36 AM](https://github.com/user-attachments/assets/f642ce86-72ec-46de-8ee0-47d212fe4b5b)


### 2-Norm of a Matrix
<![WhatsApp Image 2026-02-07 at 9 13 13 AM](https://github.com/user-attachments/assets/2c111eb0-623d-4668-a45d-3f34f37da928)


### Infinity Norm of a Matrix
![WhatsApp Image 2026-02-07 at 9 14 10 AM](https://github.com/user-attachments/assets/ef8d204e-70c6-4dda-86ac-463bb863e91a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
