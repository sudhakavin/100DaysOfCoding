## Statement
```
The first line contains the number of records. After that, each entry contains the name of the candidate and 
the number of votes they got in some state. Count the results of the elections: sum the number of votes for each candidate. 
Print candidates in the alphabetical order.
```
## Sample Input
```
5
McCain 10
McCain 5
Obama 9
Obama 8
McCain 1
```
## Code
```
num={}
for i in range(int(input())):
  candidate,votes=input().split()
  num[candidate]=num.get(candidate,0)+int(votes)
for candidate,votes in sorted(num.items()):
  print(candidate,votes)
```
## Sample Output
```
McCain 16
Obama 17
```
