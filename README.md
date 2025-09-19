# GRADING_SYSTUM

def calculator(a, b, operator):
    if operator == "+":
        print(a + b)
    elif operator == "-":
        print(a - b)
    elif operator == "*":
        print(a * b)
    elif operator == "/":
        if b != 0:
            print(a / b)
        else:
            print("Error: Division by zero")
    else:
        print("Invalid operator")

calculator(2, 5, "+")   # Output: 7
calculator(10, 3, "-")  # Output: 7
calculator(4, 6, "*")   # Output: 24
calculator(8, 2, "/")   # Output: 4.0
