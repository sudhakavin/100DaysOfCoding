## Statement
```
Given a list of numbers, print all its even elements. Use a for-loop that iterates over the list itself and not over its indices.
That is, don't use range()
```
## Sample Input
```
1 2 2 3 3 3 4
```
## Code
```
list_num=[int(i) for i in input().split()]
for j in list_num:
  if(j%2==0):
    print(j)
```
## Sample Output
```
2 2 4
```
