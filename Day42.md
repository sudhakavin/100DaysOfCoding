## Statement
```
Given a list of numbers, swap adjacent elements in each pair (swap A[0] with A[1], A[2] with A[3], etc.).
Print the resulting list. If a list has an odd number of elements, leave the last element intact.
```
## Sample Input
```
1 2 3 4 5
```
## Code
```
list_num = [int(i) for i in input().split()]
for j in range(0,len(list_num),2):
  pop_val=list_num.pop(j)
  list_num.insert(j+1,pop_val)
print(list_num)  
```
## Sample Output
```
2 1 4 3 5
```
