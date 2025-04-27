# Norm of a matrix
## Aim:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

## Program:

Developed by: Franklin.F
Reg no: 212224240041

# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)
```


# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)

```

# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)
```

Output:
1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/2ead6f64-e675-459c-a7f5-dd2130e31060)



2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/5a7e0a8e-bd56-4e6e-8455-86ac6c7b11e5)


Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/cf7b82b9-b4dd-481b-b1ca-1ee8e2adfb03)


## Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
