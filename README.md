# INVERSE-OF-A-MATRIX

## Aim:

To write a python program to find the inverse of a matrix

## Equipment’s required:

1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : Import the NumPy library.

### Step 2: Define the given matrix using a NumPy array.

### Step 3: Use np.linalg.inv() to find the inverse of the matrix.

### Step 4: Print the inverse of the matrix and end the program.

## Program:

```
#Program to find the inverse of a matrix
#Developed By: Shankar Narayana B
#Register Number: 25009078

import numpy as np

A = np.array([
    [2, 1, 1],
    [1, 1, 1],
    [1, -1, 2]
])

A_inv = np.linalg.inv(A)

print(A_inv)


```

## Output:

![alt text](exp-3.png)

## Result:

Thus the inverse of given matrix is successfully solved using python program
