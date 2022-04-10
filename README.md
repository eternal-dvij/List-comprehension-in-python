# hackerrank



# List-comprehension-in-python

# hackerrankaolution for list comprehension

```python

if __name__ = '__main__':
x = int(input())
y = int(input())
z = int(input())
n = int(input())

print([[a, b, c] for a in range(x+1) for b in range(y+1) for c in range(z+1) if(x+y+z! =n)])
```

# runner up score
```python

if __name__ = '__main__':
n = int(input())
arr = list(map((int, input().split()))
	#updated the code from arr = map((int, input().split()) to
	#arr = list(map((int, input().split())) to check the length as map() doesn't support the len() function
if(n>=2 and n<=10):
if(len(arr)>=-100 and len(arr)<=100):
a = max(arr)
#stored the max value in a variable in case there are many same values of max then we have to delete all of them
# del arr[arr.index(max(arr))]   of this statement is added at this position it will give the same result 
```
** think why we have not addes the statement "del arr[arr.index(max(arr))]" in the code **
```python
while(max(arr)==a):
del arr[arr.index(max(arr))]
print(max(arr))
```
	

Given an array of integers, calculate the ratios of its elements that are positive, negative, and zero. Print the decimal value of each fraction on a new line with 6 places after the decimal.
 
Note: This challenge introduces precision problems. The test cases are scaled to six decimal places, though answers with absolute error of up to 10^-4 are acceptable.
 
Example
arr = [1,1,0,-1,-1]
 
There are n = 5 elements, two positive, two negative and one zero. Their ratios are 2/5 = 0.400000 2/5 = 0.400000,  and 1/5 = 0.200000 . Results are printed as:
 
0.400000
0.400000
0.200000
 
Function Description
 
Complete the plusMinus function in the editor below.
 
plusMinus has the following parameter(s):
 
int arr[n]: an array of integers
Print
Print the ratios of positive, negative and zero values in the array. Each value should be printed on a separate line with 6 digits after the decimal. The function should not return a value.
 
Input Format
 
The first line contains an integer, n , the size of the array.
The second line contains n space-separated integers that describe arr[n]
 
 
 
 
 
 ```python
 
#!/bin/python3
 
import math
import os
import random
import re
import sys
 
#
# Complete the 'plusMinus' function below.
#
# The function accepts INTEGER_ARRAY arr as parameter.
#
 
def plusMinus(arr):
    positive=0;
    negative=0;
    zero=0;
    for i in range(len(arr)):
        if(arr[i]>0):
            positive+=1
        elif(arr[i]<0):
            negative+=1
        else:
            zero+=1
    # p = float(positive/len(arr))
    # n = float(negative/len(arr))
    # z = float(zero/len(arr))
    print(round(float(positive/len(arr)), 6))
    print(round(float(negative/len(arr)), 6))
    print(round(float(zero/len(arr)), 6))
   # print(float(positive/len(arr)))
   # print(float(negative/len(arr)))
   # print(float(zero/len(arr)))
            
 
if __name__ == '__main__':
    n = int(input().strip())
 
    arr = list(map(int, input().rstrip().split()))
 
    plusMinus(arr)
```


