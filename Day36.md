## Statement
```
Given a list of non-zero integers, find and print the first adjacent pair of elements that have the same sign. 
If there is no such pair, print 0.
```
## Sample Input1
```
-1 2 3 -1 -2
```
## Sample Input2
```
1 -3 4 -2 1
```
## Code
```
s = input()
lst = list(map(int, s.split()))
i = 1

for i in range(1, len(lst)):
  if lst[i] * lst[i-1] > 0:
    print(str(lst[i - 1]), str(lst[i]))
    break
  elif i == len(lst)-1:
    print("0")
```
## Sample Output1
```
2 3
```
## Sample Output2
```
0
```
