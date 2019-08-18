## Statement
```
Given a list of numbers, find and print all its elements with even indices (i.e. A[0], A[2], A[4], ...).
```
## Sample Input
```
5 6 7 8 9
```
## Code
```
list_num=[int(i) for i in input().split()]
print(list_num[0: :2])
```
## Sample Output
```
5 7 9
```
