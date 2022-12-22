# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the math module to use the built in functions for calculation
### Step 2:
Create two variables and assign the given point values to the variables
### Step 3:
Create another variable for using the  math function and use math.sqrt() to get the solution 
### Step 4:
Substitute the values in the distance formula  ![formula](/formula.png)
to get the solution 
### Step 5:
By using 'print' command display the result
### Step 6: 
End the program  
### PROGRAM:
``` python
#Program to find the distance between two points.
#Developed by: Mukesh V
#RegisterNumber:22008323
import math
l1=[4,2]
l2=[10,6]
d=math.sqrt(((l2[0]-l1[0])**2) + ((l2[1]-l1[1])**2))
print ("{:.2f}".format(d))
```
### OUTPUT:
![model](/distance.png)


### RESULT:
Thus the distance between two points value is successfully executed
