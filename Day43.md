## Statement
```
Given a list of distinct numbers, swap the minimum and the maximum and print the resulting list.
```
## Sample Input
```
3 4 5 2 1
```
## Code
```
list_num = [int(i) for i in input().split()]
minimum=list_num.index(min(list_num))
maximum=list_num.index(max(list_num))
list_num[minimum],list_num[maximum]=list_num[maximum],list_num[minimum]
print(list_num)
```
## Sample Output
```
3 4 1 2 5
```
