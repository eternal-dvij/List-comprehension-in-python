# List-comprehension-in-python

#hackerrankaolution for list comprehension

```python

if __name__ = '__main__':
x = int(input())
y = int(input())
z = int(input())
n = int(input())

print([[a, b, c] for a in range(x+1) for b in range(y+1) for c in range(z+1) if(x+y+z! =n)])
