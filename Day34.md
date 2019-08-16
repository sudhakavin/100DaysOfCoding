## Statement
```
Given a string in which the letter h occurs at least twice, reverse the sequence of characters
enclosed between the first and last occurrences of it.
```
## Sample Input
```
In the hole in the ground there lived a hobbit
```
## Code
```
s=input()
r=s[s.find('h'):s.rfind('h')]
print(s[:s.find('h')+1] + r[::-1] + s[s.rfind('h')+1:])
```
## Sample Output
```
In th a devil ereht dnuorg eht ni eloh ehobbit
```
