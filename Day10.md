## Statement
```
Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.
```
## Sample Input1
```
1
1
1
2
2
2
```
## Sample Input2
```
1
2
30
1
3
20
```
## Code
```
#Read an integer:
hr1 = int(input())
min1 = int(input())
sec1 = int(input())
hr2 = int(input())
min2 = int(input())
sec2 = int(input())
total1 = ((min1 * 60) + (hr1 * 3600) + sec1)
total2 = ((min2 * 60) + (hr2 * 3600) + sec2)
#Print a value:
print(total2 - total1)
```
## Sample Output1
```
3661
```
## Sample Output2
```
50
```
