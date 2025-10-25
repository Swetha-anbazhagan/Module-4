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
r = float(input("Enter the radius of the circle: "))

class cse:
    def mech(self, radius):
        area = 3.14159 * radius ** 2
        print("Area of the circle =", area)

obj = cse()
obj.mech(r)
```
## Output
<img width="558" height="193" alt="image" src="https://github.com/user-attachments/assets/c29dadcf-2fa8-4490-8c3e-0e760c08f772" />

## Result
Thus,a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation is executed successfully.
