## Statement
```
For given integer n ≤ 9 print a ladder of n steps. The k-th step consists of the integers from 1 to k without spaces between them.
To do that, you can use the sep and end arguments for the function print().
```
## Sample Input
```
3
```
## Code
```
n=int(input())
if n<=9:
  x=""
  for i in range(1,n+1):
    i = str(i)
    x += i
    print(x)
```
## Sample Output
```
1
12
123
```
