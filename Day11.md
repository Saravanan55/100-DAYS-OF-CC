# Given three integers, print the least of them.

```
Example input
5
3
7

Example output
3

```

```
a = int(input())
b = int(input())
c =int(input())
if(a>b):
  if(b<c):
    print(b)
  else:
    print(c)
elif(b>c):
  print(c)
else: print(a)
```
