## Statement
```
JugsMugsPugs 
Write a program that receives a number on the input.
If the number is a multiple of 3, it prints "Jugs". 
If the number is a multiple of 5, it prints "Mugs".
If the number is a multiple of 7, it prints "Pugs".
If the number is a multiple of both 3 and 5, it prints "JugsMugs".
If the number is a multiple of both 3 and 7, it prints "JugsPugs".
If the number is a multiple of both 5 and 7, it prints "MugsPugs".
If the number is a multiple of both 3, 5 and 7, it prints "JugsMugsPugs".
Otherwise, it prints the number.
```
## Sample Input1
```
15
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
if(a%3==0 and a%5==0 and a%7==0):
  print("JugsMugsPugs")
elif(a%3==0 and a%5==0):
  print("JugsMugs")
elif(a%3==0 and a%7==0):
  print("JugsPugs")
elif(a%5==0 and a%7==0):
  print("MugsPugs")
elif(a%3==0):
  print("Jugs")
elif(a%5==0):
  print("Mugs")
elif(a%7==0):
  print("Pugs")
else:
  print(a)
```
## Sample Output1
```
JugsMugs
```
## Sample Output2
```
JugsMugsPugs
```
