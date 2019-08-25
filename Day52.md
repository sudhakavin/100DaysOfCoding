## Statement
```
Define a function thank_you so that it prints the equivalent of two lines of compliments. 
The function must accept an argument name which can be used within the function. 
```
## Example
```
thank_you('Adriana') -> 
You are doing good work, Adriana!
Thank you very much for your efforts on this project.

thank_you('Billy') -> 
You are doing good work, Billy!
Thank you very much for your efforts on this project.
```
## Code
```
print("You are doing good work, Adriana!")
print("Thank you very much for your efforts on this project.")

print("\nYou are doing good work, Billy!")
print("Thank you very much for your efforts on this project.")

print("\nYou are doing good work, Caroline!")
print("Thank you very much for your efforts on this project.")

def thank_you(name):
  # write your code below 
  print("You are doing good work,"+name+"!")
  print("Thank you very much for your efforts on this project.")
  pass
  
###### DO NOT EDIT ##############
n = int(input())
for _ in range(n): 
  thank_you(input())
###### DO NOT EDIT ##############
```
