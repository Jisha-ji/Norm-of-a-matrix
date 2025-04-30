# Norm of a matrix
## Aim:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
 Register No:212224230106
 
 Developed By:Jisha Bossne SJ
### 1-Norm of a Matrix
```
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
n="{:.2f}".format(a)
print(n)
```


### 2-Norm of a Matrix
```
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n="{:.2f}".format(a)
print(n)
```


### Infinity Norm of a Matrix
```
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n="{:.2f}".format(a)
print(n)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-30 215141](https://github.com/user-attachments/assets/b1038d40-ae84-4f2d-a6e9-51bd11e53d61)

### 2-Norm of a Matrix
![Screenshot 2025-04-30 215252](https://github.com/user-attachments/assets/c1065280-ce74-482c-8c00-9c14f11a74e2)

### Infinity Norm of a Matrix
![Screenshot 2025-04-30 215330](https://github.com/user-attachments/assets/1d8ecf90-a4b7-4a0f-a127-d6a2208fcc20)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
