## Statement
```
Given a list of numbers, find and print the elements that appear in it only once.
Such elements should be printed in the order in which they occur in the original list.
```
## Sample Input
```
4 3 5 2 5 1 3 5
```
## Code
```
lst = [int(s) for s in input().split()]
for i in range(len(lst)):
  for j in range(len(lst)):
    if i != j and lst[i] == lst[j]:
        break
  else:
    print(lst[i], end=' ')
 ```
 ## Sample Output
 ```
 4 2 1
```
