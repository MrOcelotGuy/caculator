# Caculator


This is my first-ever program I made 


This caculator was made with python

	print("this is a calculator")
	print("Enter 'add' to add two numbers")
	print("Enter 'subtract' to subtract two numbers")
	print("Enter 'multiply' to multiply two numbers")
	print("Enter 'divide' to divide two numbers")
	print("Enter 'quit' to end the program")
	print("You can't use more than 2 numbers in a operation")
	print("this is my first program so enjoy")
	while True:
			user_input = input(" ")

			if user_input == "add":
						 num1 = float(input("Enter a number "))
						 num2 = float(input("Enter another number "))
						 result = str(num1+num2)
						 print("The result is" + result + "!")
			elif user_input == "subtract":
						 num1 = float(input("Enter a number: "))
						 num2 = float(input("Enter another number: "))
						 result = str(num1 - num2)
						 print("The result is" + result + "!")
			elif user_input == "multiply":
						 num1 = float(input("Enter a number: "))
						 num2 = float(input("Enter another number: "))
						 result = str(num1 * num2)
						 print("The result is" + result + "!")
			elif user_input == "divide":
						 num1 = float(input("Enter a number: "))
						 num2 = float(input("Enter another number: "))
						 result = str(num1 / num2)
						 print("The result is" + result + "!")
			elif user_input == str("quit"):
							print("goodbye")
							break

			else:
						print("...")
						print("ummmmmmmmmmmmmm")
