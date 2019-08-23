## Statement
```
Given the text: the first line contains the number of lines, then given the lines of words. 
Print the word in the text that occurs most often. If there are many such words, print the one that is less in the alphabetical order.
```
## Sample Input
```
2
apple orange banana
banana orange
```
## Code
```
num=int(input())
words={}
lst=[]
for i in range(num):
  s=list(input().split())
  for j in range(len(s)):
    if s[j] not in words:
      words[s[j]]=0
    words[s[j]]+=1
for k,v in words.items():
  if v >= max(words.values()):
    lst.append(k)
print(sorted(lst)[0])  
```
## Sample Output
```
banana
```
