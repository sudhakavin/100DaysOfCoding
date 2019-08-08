## Statement
```
N students take K apples and distribute them among each other evenly. The remaining (the indivisible) part remains in the basket. How many apples will each single student get? How many apples will remain in the basket?
The program reads the numbers N and K. It should print the two answers for the questions above.
```
## Sample Input
```
6
50
```
## Code
```
# Read the numbers like this:
n = int(input())
k = int(input())
# Print the result with print()
print(k // n)
print(k % n)
```
## Sample Output
```
8
2
```
