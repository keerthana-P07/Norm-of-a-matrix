# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm for 1-Norm of a Matrix
1.Get the input matrix using np.array()
2.Find the 1-norm of the matrix using np.linalg.norm(matrix, 1)
3.Print the 1-norm of the matrix in two decimal places
## Algorithm for 2-Norm of a Matrix
1.Get the input matrix using np.array()
2.Find the 2-norm of the matrix using np.linalg.norm(matrix, 2)
3.Print the 2-norm of the matrix in two decimal places
## Algorithm for Infinity Norm of a Matrix
1.Get the input matrix using np.array()
2.Find the Infinity norm of the matrix using np.linalg.norm(matrix, np.inf)
3.Print the Infinity norm of the matrix in two decimal places
## Program:
```
# 1-Norm of a Matrix
'''
Developed by: P KEERTHANA
RegisterNumber: 212225230138
''' 
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix = np.array(eval(input()))
result = np.linalg.norm(matrix,1)
print(result)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: P KEERTHANA
RegisterNumber: 212225230138
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
matrix = np.array(eval(input()))
result = np.linalg.norm(matrix,2)
print("{:.2f}".format(result))




# Infinity Norm of a Matrix
'''
Developed by: P KEERTHANA
RegisterNumber: 212225230138 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"  
import numpy as np
matrix = np.array(eval(input()))
result = np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))
```
## Output:
### 1-Norm of a Matrix
acer/OneDrive/Pictures/Screenshots/Screenshot 2026-08-11 124511.png
### 2-Norm of a Matrix
acer/OneDrive/Pictures/Screenshots/Screenshot 2026-08-11 124550.png

### Infinity Norm of a Matrix
acer/OneDrive/Pictures/Screenshots/Screenshot 2026-08-11 124620.png

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
