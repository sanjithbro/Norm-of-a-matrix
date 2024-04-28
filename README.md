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
### Developed by :R.Sanjith
### Register No:212223230191
# Program to find 1-Norm of a matrix
```Python
Developed by :R.Sanjith
Register No:212223230191
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```python
Developed by :R.Sanjith
Register No:212223230191
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2) 
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix) 
```
# 3-Infinity Norm of a Matrix
```python
Developed by :R.Sanjith
Register No:212223230191
import numpy as  np
mat=np.array(eval(input())) 
ans=np.linalg.norm(mat,np.inf) 
norm_of_matrix="{:.2f}".format(ans) 
print(norm_of_matrix)  
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/sanjithbro/Norm-of-a-matrix/assets/167451460/c357a06f-69bb-4be6-b508-02795409e7aa)

### 2-Norm of a Matrix
![image](https://github.com/sanjithbro/Norm-of-a-matrix/assets/167451460/35b7a3b3-4031-4811-a295-cca3d057be79)

### Infinity Norm of a Matrix
![image](https://github.com/sanjithbro/Norm-of-a-matrix/assets/167451460/643c901a-6743-4247-ad30-6e3dd974b620)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
