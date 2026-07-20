# Project 1 - Simple Calculator
# Created by Dhruv Patil

# Changed int to float to support decimal numbers
first_number = float(input("Enter first number: "))
second_number = float(input("Enter second number: "))

print("Addition =", first_number + second_number)
print("Subtraction =", first_number - second_number)
print("Multiplication =", first_number * second_number)

# Added a check to prevent crashing when dividing by zero
if second_number != 0:
    print("Division =", first_number / second_number)
else:
    print("Division = Error (Cannot divide by zero)")
