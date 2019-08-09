## Statement
```
JugsMugsPugs LITE
Write a program that receives a number on the input.
  - If the number is a multiple of 3, it prints "Jugs". 
  - If the number is a multiple of 5, it prints "Mugs".
  - If the number is a multiple of 7, it prints "Pugs".
  - If the number is a multiple of both 3 and 5, it prints "JugsMugs".
  - If the number is a multiple of both 3 and 7, it prints "JugsPugs".
  - If the number is a multiple of both 5 and 7, it prints "MugsPugs".
  - If the number is a multiple of both 3, 5 and 7, it prints "JugsMugsPugs".
Otherwise, it prints the number.
LITE REQUIREMENT:
Limit your code to use only if statements and not to exceed 4 of them. 
You are a real winner if you can achieve it using not more than 3 if statements.
```
## Sample Input1
```
21
```
## Sample Input2
```
105
```
## Code
```
#Read an integer:
a=int(input())
#Print a value:
if(a%3==0):
  print("Jugs")
if(a%5==0):
  print("Mugs")
if(a%7==0):
  print("Pugs")
if(a%3!=0 and a%5!=0 and a%7!=0):
  print(a)
 ```
 ## Sample Output1
 ```
 JugsPugs
 ```
 ## Sample Output2
 ```
 JugsMugsPugs
```
