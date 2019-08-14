## Statement
```
For the given integer N calculate the following sum:
1³ + 2³ + ... + N³
```
## Sample Input
```
3
```
## Code
```
num = int(input())
res=0
for num in range(1,num+1):
  res += num**3
print(res)
```
## Sample Output
```
36
```
