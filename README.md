# python-calculator
My first Python project : a basic console calculator.
print("--- Simple Calculator ---")
print("Available operations: +, -, *, /")

operation = input("Choose an operation: ")
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

if operation == "+":
    print("Result:", num1 + num2)
elif operation == "-":
    print("Result:", num1 - num2)
elif operation == "*":
    print("Result:", num1 * num2)
elif operation == "/":
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error! Division by zero is not allowed.")
else:
    print("Invalid operation entered.")



