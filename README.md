# Multiplying-two-matrix

## AIM:

## ALGORITHM:

### Step 1:
import numpy as np
### Step 2:
 give the inputs 
### Step 3:
use the for loop and range function
### Step 4:
multiply the two matrices
### Step 5:
check and verify the program

## PROGRAM:
~~~
import numpy as np

l1,l2 =[],[]

n = int(input())

for i in range(n):

     l1.append(int (input()))

for i in range(n):
     l2.append(int (input()))
value1=np.array(l1)
value2= np.array(l2)

result = value1*value2


print("Product of two arrays is:", result)
~~~ 

## OUTPUT:
![output](tham.png)

## RESULT:
Thus the program is written to multiply two matrices using python programming


