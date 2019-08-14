## Statement
```
Given a sequence of distinct non-negative integers, where each number is written in a separate line.
The sequence ends with 0. Print the second largest element in this sequence. It is guaranteed that the sequence has at least two elements.
```
## Sample Input
```
1
7
9
0
```
## Code
```
first_num=1
second_num=1
number=1
second_num=0
while number!=0:
  number=int(input())
  if second_num<number<first_num:
    second_num=number
  elif number>first_num:
    second_num=first_num
    first_num=number
print(second_num)    
```
## Sample Output
```
7
```
