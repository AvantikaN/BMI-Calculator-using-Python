# BMI-Calculator-using-Python

BMI is a screening tool that can indicate whether a person is underweight or if they have a healthy
weight, excess weight, or obesity. If a person’s BMI is outside of the healthy range, their health
risks may increase significantly.
To calculate BMI in metric units, use the following method: BMI = kg/m2
So, to calculate an adult’s BMI: Divide their weight in kilograms (kg) by the square of their height
in meters (m2)

There are two functions used to display the BMI result:

1. calculate_bmi():
Kg = int(weight_tf.get())
This line of code gets the user weight, converts it to integer, and then stores the value in the variable kg.
m= int(height_tf.get())/100
This line of code gets the user height, converts into integer, divides the result with 100 so that centimeters
become meters, and then stores it in a variable m.
bmi=kg/(m*m)
This is the formula for finding BMI. We have stored the formula in a variable BMI.
bmi=round(bmi, 1)
Before round off, the result was appearing in multiple decimal values. But after using the round function it
looks simplified and easy to read.
Without round function, the result appeared is 20.061728395061728 and after applying the round function
the result appeared is 20.1.

2. bmi_index(bmi)
We have called the bmi_index() function to compare the BMI value with the BMI categories.
bmi_index():
In this function, the final result displayed depending upon the BMI value & BMI category it
belongs to.BMI Categories:

Underweight = <18.5
Normal weight = 18.5–24.9
Overweight = 25–29.9
Obesity = BMI of 30 or greater

![image](https://github.com/AvantikaN/BMI-Calculator-using-Python/assets/99970466/d88a9995-828e-4ca0-94a2-7c42c0218f3e)
