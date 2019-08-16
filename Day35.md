## Statement
```
Given a string in which the letter h occurs at least twice, replace every occurrence of the letter h by the letter H,
except for the first and the last ones.
```
## Sample Input
```
In the hole in the ground there lived a hobbit
```
## Code
```
s=input()
r=s[s.find('h')+1:s.rfind('h')]
print(s[:s.find('h')+1] + r.replace('h','H') + s[s.rfind('h'):])
```
## Sample Output
```
In the Hole in tHe ground tHere lived a hobbit
```
