## Statement
```
Given a three-digit number. Find the sum of its digits.
```
## Sample Input
```
123
```
## Code
```
# Read an integer:
N =int(input())
#Calculation of Sum of digits: 
digit1 = N%10
N =int(N/10)
digit2 = N%10
N =int(N/10)
digit3 = N
# Print a value:
print(digit1 + digit2 + digit3)
```
## Sample Output
```
6
```
