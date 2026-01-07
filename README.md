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
# Register No:
# Developed By:
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
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1009" height="613" alt="Screenshot 2026-01-07 150328" src="https://github.com/user-attachments/assets/be9eb789-03b3-4c2b-ada8-63b3352d681e" />

<br>
<br>

### 2-Norm of a Matrix
<img width="607" height="754" alt="Screenshot 2026-01-07 150346" src="https://github.com/user-attachments/assets/4c850770-8be2-4ab5-88ca-f767f3135faf" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="818" height="537" alt="Screenshot 2026-01-07 150357" src="https://github.com/user-attachments/assets/61b55a57-9f24-4fc0-bee9-6575b4a2ef0d" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
