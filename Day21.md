## Statement
```
JugsMugsPugs Plus
Write a program that receives a number on the input.
  - If the number is a multiple of 3, or it contains digit 3, it prints "Jugs". 
  - If the number is a multiple of 5, or it contains digit 5, it prints "Mugs".
  - If the number is a multiple of 7, or it contains digit 7, it prints "Pugs".
Otherwise, it prints the number.
SPECIAL REQUIREMENT: 
Try and limit the number of conditional statements to not more than 4. 
And use only one print statement.
```
## Sample Input1
```
73 
```
## Sample Input2
```
51  
```
## Code
```
#Read an integer:
a=int(input())
#Print a value:
if(a%3==0 or '3' in str(a)):
  print("Jugs",end='')
if(a%5==0 or '5' in str(a)):
  print("Mugs",end='')
if(a%7==0 or '7' in str(a)):
  print("Pugs",end='')
```
## Sample Output1
```
JugsPugs
```
## Sample Output2
```
JugsMugs
```
