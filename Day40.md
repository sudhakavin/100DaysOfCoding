## Statement
```
Given a list of numbers, determine and print the number of elements that are greater than both of their neighbors.
The first and the last items of the list shouldn't be considered because they don't have two neighbors.
```
## Sample Input
```
1 5 1 5 1
```
## Code
```
list_num=[int(i) for i in input().split()]
count=0
for j in range(1,len(list_num)-1):
  if(list_num[j-1]<list_num[j]>list_num[j+1]):
    count+=1
print(count)  
```
## Sample Output
```
2
```
