# Given a three-digit number. Find the sum of its digits.

```
Example input
123

Example output
6

```

```
a=int(input())
tot=0
while(a>0):
  rem=a%10
  tot=rem+tot
  a=a//10
print(tot)
```
