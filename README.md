# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Get the input values from the user
### Step 2: 
Assign the values to the respective points
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Display the output
### PROGRAM:
```
Developed By : KrishnaPrasad.S
Register No : 212223230108
```
```
import math
x1= int(input("Enter the first point : "))
y1 = int(input())
x2 = int(input("Enter the second point : "))
y2 = int(input())
value = (x2 - x1)**2 + (y2 - y1)**2
ans = math.sqrt(value)
print(f"The distance between ({x1},{y1}) and ({x2},{y2}) is {ans:.2f}")

```
  


### OUTPUT:
![image](https://github.com/KrishnaPrasad148/DISTANCE-BETWEEN-TWO-POINTS/assets/147332763/cee5aac1-0b13-4f24-a91c-d436c805f467)



### RESULT:
Thus the Distance between of two points is successfully calculated 
