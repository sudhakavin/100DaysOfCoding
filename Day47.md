## Statement
```
You are given a dictionary consisting of word pairs. Every word is a synonym of the other word in its pair. 
All the words in the dictionary are different.
After the dictionary there's one more word given. Find a synonym for it.
```
## Sample Input
```
3
Hello Hi
Bye Goodbye
List Array
Goodbye
```
## Code
```
num = int(input())
s={}
for i in range(num):
  first,second=input().split()
  s[first]=second
  s[second]=first
print(s[input()])  
```
## Sample Output
```
Bye
```
