# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.

## EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7

## ALGORITHM:

### Step 1:
Import the numpy module to use the built-in functions for calculation
### Step 2:
Get input from the user.
### Step 3:
Create empty lists l1 and l2.
### Step 4:
Use for loop to append the values into the list.
### Step 5:
Create array using the list.
### Step 6:
Multiply two array.
### Step 7:
Print the product of two arrays.

## PROGRAM: 
```python
'''
Program to multiply two matrix.
Developed by: R LAKSHANA
RegisterNumber: 22004909
'''
import numpy as np
n= int(input())
l1, l2 = [],[]
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
array1 = np.array(l1)
array2 = np.array(l2)
product = array1*array2
print("Product of two arrays is:",product)
```

## OUTPUT:

![output](/Output.png)

## RESULT:
Thus the program for multiplying two matrix is written and verified using python programming.
