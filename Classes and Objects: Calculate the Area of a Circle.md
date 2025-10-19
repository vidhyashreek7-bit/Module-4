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
class cse:
    def __init__(self,r):
        self.r=r
    def mech(self):
        c=3.141592*self.r*self.r
        print(f"Area of circle: {c:.2f}")
        
r=int(input())
obj=cse(r)
obj.mech()
```

## Output
<img width="880" height="404" alt="image" src="https://github.com/user-attachments/assets/da71bb27-a846-40ca-ae64-59fb4ebf376a" />


## Result
Thus the program is executed successfully.
