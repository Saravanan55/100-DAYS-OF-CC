# Write a program to calculate the distance between two points.

```

INPUT 
4
0
0
0

OUTPUT
4


INPUT 
0
0
4
3

OUTPUT
5
```

```
import math
# get the x coordinate of Point 1
x1 = int(input())  
# get the y coordinate of Point 2
y1 = int(input())  
# get the x coordinate of Point 2
x2=int(input())
# get the y coordinate of Point 2
y2 = int(input())

distance=((x2-x1)**2+(y2-y1)**2)
print(math.sqrt(distance))
```
