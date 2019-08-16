## Statement
```
Given a string in which the letter h occurs at least twice. Remove from that string the first and 
the last occurrence of the letter h, as well as all the characters between them.
```
## Sample Input
```
In the hole in the ground there lived a hobbit
```
## Code
```
s=input()
r=s.replace(s[s.find('h'):s.rfind('h')+1],'')
print(r)
```
## Sample Output
```
In tobbit
```
