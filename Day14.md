## Statement
```
Given three integers, print the least of them.
```
## Sample Input
```
5
3
7
```
## Code
```
# Read an integer:
a = int(input())
b = int(input())
c = int(input())
#Print a Least value: 
if(a<b and a<c):
  print(a)
elif(b<c and b<a ):  
  print(b)
else:
  print(c)
```
## Sample Output
```
3
```
