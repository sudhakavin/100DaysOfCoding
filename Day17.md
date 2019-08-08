## Statement
```
Jugs for Three
Write a program that receives a number on the input.
If the number is a multiple of 3, it prints "Jugs". 
Otherwise, it prints the number.
```
## Sample Input
```
33
```
## Code
```
#Read an integer:
a = int(input())
#Print "Jugs" if an integer is a multiple of 3:
if(a%3 == 0):
  print("Jugs")
else:
  print(a)
```
## Sample Output
```
Jugs
```
