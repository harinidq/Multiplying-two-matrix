# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.

## ALGORITHM:

### Step 1:
import num as np.
### Step 2:
create two empty lists.
### Step 3:
Get input from user.
### Step 4:
Create a nested for loop and append the values to the created lists.
### Step 5:
Create two arrays.
### Step 6:
Multiply the two arrays.
### Step 7
Give print statement.

## PROGRAM:
```
#Developed by:m.d.harini
#Registration no:22001980

import numpy as np
n=int(input())
l1,l2=[],[]
for i in range(n):
    l1.append(int(input()))
for i in range (n):
    l2.append(int(input()))
array1=np.array(l1)
array2=np.array(l2)
product=array1*array2
print("Product of two arrays is:",product)
```

## OUTPUT:
![Screenshot from 2022-10-10 14-09-25](https://user-images.githubusercontent.com/113497680/194827893-3dd4adf5-9039-4733-9257-d055dea3a6f8.png)

## RESULT:
Hence the program is runned successfully...
