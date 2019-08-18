## Statement
```
Given a list of numbers, find and print all its elements that are greater than their left neighbor.
```
## Sample Input
```
1 5 2 4 3
```
## Code
```
list_num=[int(i) for i in input().split()]
j=0
while j<len(list_num):
  if(list_num[j]>list_num[j-1] and j>0):
    print(list_num[j],end="")
  j+=1    
```
## Sample Output
```
5 4
```
