
#Task 1: Perform Basic Mathematical Operations
#functionality:
This is a basic arithmetic calculator written in Python. It performs four operations: addition, subtraction, multiplication, and division.
Input Collection:
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
The program prompts the user to enter two numbers.

input() reads the input as a string.

int() converts that string to an integer.

So now, a and b are integers that the user entered.

Display Heading:
print("Result:")
This is just a label to show that the following lines are the results of the calculations.

Addition:
print("Addition: ", a + b)
Adds a and b, then prints the result.

Subtraction:
print("Subtraction: ", a - b)
Subtracts b from a, then prints the result.

Multiplication:
print("multiplication: ", a * b)
Multiplies a and b, then prints the result.

Division:
print("division: ", a / b)
Divides a by b, then prints the result as a floating-point number


#Task 2: Create a Personalized Greeting
This is a simple Python greeting program. It asks the user for their first and last name, then displays a personalized welcome message.

 Line-by-Line Explanation
User Input – First Name
first_name = input("Enter your first name: ")
The program displays the message: "Enter your first name: ".

It waits for the user to type their first name.

The user's input is stored in the variable first_name as a string.

User Input – Last Name
last_name =  input("Enter your last name: ")
Similar to the first step, the program now asks: "Enter your last name: ".

The input is stored in the variable last_name.

Greeting Message:
print("Hello, ", first_name + last_name, "! welcome to the python program")
The program prints a welcome message using the two names.

first_name + last_name joins the first and last names without a space.

For example, if you entered "John" and "Smith", it would output:
Hello, JohnSmith! welcome to the python program.














