## Statement
```
Given the integer N - the number of seconds that is passed since midnight - how many full hours and full minutes are passed since midnight?
The program should print two numbers: the number of hours (between 0 and 23) and the number of minutes (between 0 and 1339).
For example, if N = 3900, then 3900 seconds have passed since midnight. 
Therefore, the time now is 1:05am. 
So the program should print 1 65 - 1 full hour is passed since midnight, 65 full minutes passed since midnight.  
```
## Sample Input
```
3900
```
## Code
```
#Read an Integer:
N = int(input())
n = N//60
H = n//60
#Print a value:
print(str(H)+''+str(n))
```
## Sample Output
```
65
```
