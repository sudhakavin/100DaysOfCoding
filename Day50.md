## Statement
```
Given a list of countries and cities of each country, then given the names of the cities.
For each city print the country in which it is located.
```
## Sample Input
```
2
USA Boston Pittsburgh Washington Seattle
UK London Edinburgh Cardiff Belfast
3
Cardiff
Seattle
London
```
## Code
```
location={}
for i in range(int(input())):
  country,*cities=input().split()
  for city in cities:
    location[city]=country
    
for i in range(int(input())):
  print(location[input()])
```
## Sample Output
```
UK
USA
UK
```
