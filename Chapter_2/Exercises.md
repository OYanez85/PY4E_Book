## 🧪 Exercise 2

**Write a program that uses input to prompt a user for their name and then welcomes them.**

```python
name = input("Enter your name: ")
print("Hello", name)

🧮 Exercise 3

**Write a program to prompt the user for hours and rate per hour to compute gross pay.**

hours = float(input("Enter Hours: "))
rate = float(input("Enter Rate: "))
pay = hours * rate
print("Pay:", pay)

Optional: Round to two decimal places:

print("Pay:", round(pay, 2))

📏 Exercise 4

**Evaluate expressions with given values:**

width = 17
height = 12.0

Expression analysis:

    width // 2 → Integer division
    Value: 8
    Type: int

    width / 2.0 → Float division
    Value: 8.5
    Type: float

    height / 3 → Float division
    Value: 4.0
    Type: float

    1 + 2 * 5 → Order of operations (PEMDAS)
    Value: 11
    Type: int

🌡️ Exercise 5

Write a program to convert Celsius to Fahrenheit.

Formula:
Fahrenheit = Celsius * 9/5 + 32

celsius = float(input("Enter temperature in Celsius: "))
fahrenheit = celsius * 9 / 5 + 32
print("Temperature in Fahrenheit:", fahrenheit)
