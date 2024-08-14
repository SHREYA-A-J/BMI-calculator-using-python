# BMI-calculator-using-python
weight = float(input("Enter weight in kg"))
height = float(input("Enter height in cm"))

height_in_metres = height /100
bmi = weight /(height_in_metres ** 2)

print("Your BMI is:", bmi)

if bmi <= 18.5:
    print("you are in under weight!!!")
elif 18.5 <= bmi < 25:
    print("You are a normal weight")
elif 25 <= bmi < 30:
    print("You are overweight")
else:
    print("You are obese")
