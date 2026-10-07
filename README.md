# Bitantos_ModularCalculator

def add_numbers(num1, num2):
    return num1 + num2

def subtract_numbers(num1, num2):
    return num1 - num2

def multiply_numbers(num1, num2):
    return num1 * num2
  
def divide_numbers(num1, num2):
    return num1 * num2

number_1 = float(input("Enter number 1: "))
number_2 = float(input("Enter number 2: "))
choice = input("Choose operation (addition, subtraction, multiplication or division): ").lower().strip()

if choice == "addition": 
    output = add_numbers(number_1, number_2)
    print("sum =", output)

elif choice == "subtraction":
    output = subtract_numbers(number_1, number_2)
    print("difference =", output)

elif choice == "multiplication":
    output = multiply_numbers(number_1, number_2)
    print("product =", output)

elif choice == "division":
    output = divide_numbers(number_1, number_2)
    print("product =", output)


else:
    print("Invalid operation selected.")

   # In my calculator program, I made four functions: add_numbers, subtract_numbers, multiply_numbers, and divide_numbers. All of them used num1 and num2 as parameters. When I actually called the functions, the arguments passed in were number_1 and number_2, which were the numbers the user typed. My program took the returned value, saved it in a variable called output, and printed it out as the answer. It is way better to use functions instead of one big block of code because it keeps everything organized. If something breaks, it's super easy to find the glitch and fix it in one small spot without messing up the whole project.

