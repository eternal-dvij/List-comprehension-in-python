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
	




