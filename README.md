# Inverse-of-matrix

## AIM:
To write a program to perform Inverse-of-matrix using python programming.
## ALGORITHM:
### Step 1:
Import Numpy module as np.
### Step 2:
Create empty lists.
### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Print the inverse of the array using np.linalg.inv
## PROGRAM:
```
To write a python program to find the inverse of a matrix.
Developed by:  Evangelin.S
Register Number: 212221230025

import numpy as np
rows=int(input())
columns=int(input())
l1=[]
for i in range(rows):
    temp=[]
    for j in range(columns):
        t=int(input())
        temp+=[t]
    l1+=[temp]
print(l1)
print(np.linalg.inv(l1))
```
## OUTPUT:
![inverse](https://user-images.githubusercontent.com/94219798/153698750-a6a9d772-2791-438b-8a3a-7a2f775ea5e6.JPG)

## RESULT:
Thus the program is written to perform Inverse-of-matrix using python programming.
