# Classes and Objects in Python: Calculate the Area of a Circle

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
    def mech(self):
        radius=float(input())
        area=math.pi*(radius**2)
        print("Area of circle: {:.2f}".format(area))
obj=cse()
obj.mech()
```

## Output
<img width="1915" height="522" alt="Screenshot 2025-10-18 235419" src="https://github.com/user-attachments/assets/9d9ba48b-e000-4c1f-a5c6-d36edba81b69" />

## Result
The Classes and Objects in Python: Calculate the Area of a Circle is executed successfully.
