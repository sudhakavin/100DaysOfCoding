## Statement
```
JugsMugs for Three and Five
Write a program that receives a number on the input.
If the number is a multiple of 3, it prints "Jugs". 
If the number is a multiple of 5, it prints "Mugs".
If the number is a multiple of both 3 and 5, it prints "JugsMugs".
Otherwise, it prints the number.
```
## Sample Input1
```
3 
```
## Sample Input2
```
15
```
## Sample Input3
```
112
```
## Code
```
a=int(input())
if(a%3 == 0 and a%5==0):
  print("JugsMugs")
elif(a%3==0):
  print("Jugs")
elif(a%5==0):
  print("Mugs")
else:
  print(a)
```
## Sample Output1
```
Jugs
```
## Sample Output2
```
JugsMugs
```
## Sample Output3
```
112
```
