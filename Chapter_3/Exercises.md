Python Exercises – Chapter 3.11 Solutions

Exercise 1: Overtime Pay Calculation

Rewrite your pay computation to give the employee 1.5 times the hourly rate for hours worked above 40.

hours = float(input("Enter Hours: "))
rate = float(input("Enter Rate: "))

if hours > 40:
    overtime = hours - 40
    pay = (40 * rate) + (overtime * rate * 1.5)
else:
    pay = hours * rate

print("Pay:", pay)

Exercise 2: Input Validation with try/except

Rewrite your pay program using try and except so that your program handles non-numeric input gracefully by printing a message and exiting.

try:
    hours = float(input("Enter Hours: "))
    rate = float(input("Enter Rate: "))
    
    if hours > 40:
        overtime = hours - 40
        pay = (40 * rate) + (overtime * rate * 1.5)
    else:
        pay = hours * rate

    print("Pay:", pay)

except:
    print("Error, please enter numeric input")

Exercise 3: Score to Grade Converter

Write a program to prompt for a score between 0.0 and 1.0. If the score is out of range, print an error message. If the score is between 0.0 and 1.0, print a grade based on the following table:

Score
Grade
≥ 0.9 A
≥ 0.8 B
≥ 0.7 C
≥ 0.6 D
< 0.6 F

try:
    score = float(input("Enter score: "))
    
    if score > 1.0 or score < 0.0:
        print("Bad score")
    elif score >= 0.9:
        print("A")
    elif score >= 0.8:
        print("B")
    elif score >= 0.7:
        print("C")
    elif score >= 0.6:
        print("D")
    else:
        print("F")

except:
    print("Bad score")

