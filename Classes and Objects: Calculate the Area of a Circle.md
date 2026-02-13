

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math

class cse:
    def mech(self, r):
        area = math.pi * r * r
        print("Area of the circle is:", area)

radius = float(input("Enter the radius of the circle: "))
obj = cse()
obj.mech(radius)


```
Add code here

## Output
<img width="483" height="176" alt="image" src="https://github.com/user-attachments/assets/377b2292-94d3-4e7c-bfe4-50f408ceda69" />

## Result
The program successfully calculates the area of a circle using a Python class cse and its method mech. The user provides the radius, and the method computes and prints the area using the formula
