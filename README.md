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
``````
# Register No:2008727
# Developed By:Dhivya Dharshini B
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,1)
print("%.2f"%sol)
``````
# 2-Norm of a Matrix
``````
#Program to find 2-norm of a matrix.
#Developed by:Dhivya Dharshini.B
#RegisterNumber:2008727 
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,2)
print("%.2f"%sol)
``````
# Infinity Norm of a Matrix
``````
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,np.inf)
print("%.2f"%sol)
``````
## Output:
### 1-Norm of a Matrix
![output](/Screenshot%202023-12-24%20132525.png)

### 2-Norm of a Matrix
![output](/Screenshot%202023-12-24%20132551.png)
### Infinity Norm of a Matrix
![output](/Screenshot%202023-12-24%20132611.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
