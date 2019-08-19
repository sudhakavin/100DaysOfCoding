## Statement
```
The text is given in a single line. For each word of the text count the number of its occurrences before it.
```
## Sample Input
```
one two one two three two four three
```
## Code
```
def occurrence(s):
   count = {}
   string = ''
   for word in s.split():
      count[word] = count.get(word, 0) + 1
      string += str(count[word] - 1) +' '
   return string

print(occurrence(input()))
```
## Sample Output
```
0 0 1 1 0 2 0 1
```
