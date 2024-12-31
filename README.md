while True:

    try:
        num1 = float(input("Insert the first number : "))
    except :
        print("Invalid input")
        quit()
    try:
        operator = input("what operation you wnat ? : ")
    except:
        print("Invalid input")
        quit()
    try:
        num2 = float(input("Insert the second number : "))
    except :
        print("Invalid input")
        quit()


    if operator == "+":
        print(num1 + num2)
    elif operator == "-":
        print(num1 - num2)
    elif operator == "*":
        print(num1 * num2)
    elif operator == "/":
        print(num1 / num2)
