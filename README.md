# simple-calcus
print("-------Simple calculator-------")

print(" ")
print("""1.Addition
2.Subraction
3.Multiplication
4.Division
5.Exponetials
6.Quit""")
print(" ")
print('Select an option(1-5) and "6" to quit.')
def simplecalcus():
    
    while True:
       try:
          print(" ")
          option = float(input("User's option:"))
          if option == 1:
             num1 = float(input("Enter first number:"))
             num2 = float(input("Enter second number:"))
             print(f"The result is [{num1 + num2}].")
          elif option == 2:
             num3 = float(input("Enter first number:"))
             num4 = float(input("Enter second number:"))
             print(f"The result is [{num3 - num4}].")
          elif option == 3:
             num5 = float(input("Enter first number:"))
             num6 = float(input("Enter second number:"))
             print(f"The result is [{num5 * num6}].")
          elif option == 4:
             num7 = float(input("Enter first number:"))
             num8 = float(input("Enter second number:"))
             print(f"The result is [{num7 / num8}].")
          elif option == 5:
             num9 = int(input("Enter base number:"))
             num10 = int(input("Enter power number:"))
             print(f"The result is [{num9 ** num10}].")
          elif option == 6:
             print("Thanks for using this calculator. Goodbye!")
             break
          else:
             print("Invalid Input. Enter a number from 1-6.")
       except ZeroDivisionError:
           print("Undefined")
       except NameError:
         print("Dont Understand")
       except ValueError:
         print("Dont Understang.")
simplecalcus()



