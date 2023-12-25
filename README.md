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
# Register No:23013437
# Developed By: GOWTHAM N
# 1-Norm of a Matrix
~~~
'''
Pogram to find 1-norm of a matrix.
Developed by : GOWTHAM N
RegisterNumber : 23013437
'''
import numpy as np
m=np.array(eval(input()))
res=np.linalg.norm(m,1)
matrix="{:.2f}".format(res)
print(matrix)
~~~

# 2-Norm of a Matrix
~~~
'''
Program to find 2-norm of a matrix.
Developed by: GOWTHAM N
RegisterNumber: 23013437
'''
import numpy as np
g=np.array(eval(input()))
ans=np.linalg.norm(g,2)
matrix="{:.2f}".format(ans)
print(matrix)
# Type your code here
~~~




# Infinity Norm of a Matrix
~~~
'''
Program to find Infinity of a mtrix.
Developed by: GOWTHAM N
RegisterNumber :23013437
'''
import numpy as np
n=np.array(eval(input()))
r=np.linalg.norm(n,np.inf)
output="{:.2f}".format(r)
print(output)
~~~
```
## Output:
### 1-Norm of a Matrix
![OUTPUT](https://github.com/GOWTHAM54577/Norm-of-a-matrix/assets/144589420/f0520b65-5aad-41c3-b353-a0da821cb166)
### 2-Norm of a Matrix
![OUTPUT](https://github.com/GOWTHAM54577/Norm-of-a-matrix/assets/144589420/922d4ecc-b2ea-45db-86af-dd28748e2c52)
### Infinity Norm of a Matrix
![OUTPUT](https://github.com/GOWTHAM54577/Norm-of-a-matrix/assets/144589420/3a20b64b-45e6-4a83-9218-162448254fd4)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
