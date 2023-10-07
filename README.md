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
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)
```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: jeevanesh
RegisterNumber: 
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)
```

# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```
## Output:
![image](https://github.com/plotswag/Norm-of-a-matrix/assets/145822344/c6c79c72-650f-4647-b592-09d475e36d25)
![image](https://github.com/plotswag/Norm-of-a-matrix/assets/145822344/83a57c13-5a30-45f3-ad69-7d4b168facec)
![image](https://github.com/plotswag/Norm-of-a-matrix/assets/145822344/ddcdfc43-b103-411d-9407-a0392b40acc1)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
