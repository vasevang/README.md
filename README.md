# README.md
#calculator vol.2
def addition(x, y):
    return x+y
def subtraction(x,y ):
    return x-y
def multiplication(x, y):
    return x*y
def division(x,y):
    return x/y

#main
times = int(input("How many operations do you want to do?:"))
for i in range(times):
    number1 = int(input('Enter a number: '))
    number2 = int(input('Enter a second number: '))
    operation = input('Choose an operation(+, -, *, /): ')
    if operation == '+':
        print("Result:",addition(number1, number2))
    elif operation == '-':
        print("Result:",subtraction(number1, number2))
    elif operation == '*':
        print("Result:",multiplication(number1, number2))
    elif operation == '/':
        print("Result:",division(number1, number2))
