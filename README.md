# Task 1: Print a greeting message
print("Hello, welcome to the Python basics demo!")

# Task 2: Variables and Data Types
age = 27            # Integer
height = 170        # Height in cm
name = "Baysaa"     # String
is_student = True   # Boolean (change to False if not a student)

print("Name:", name)
print("Age:", age)
print("Height:", height, "cm")
print("Is student:", is_student)

# Task 3: Get User Input and Display a Custom Message
user_name = input("What is your name? ")
print("Nice to meet you, " + user_name + "!")

# Task 4: Basic Arithmetic Operations
num1 = 10
num2 = 5
print("Addition:", num1 + num2)
print("Subtraction:", num1 - num2)
print("Multiplication:", num1 * num2)
print("Division:", num1 / num2)

# Task 5: If-Else Conditional
temperature = int(input("Enter the current temperature: "))

if temperature > 30:
    print("It's a hot day!")
elif temperature < 15:
    print("It's a cold day!")
else:
    print("It's a nice day!")

# Task 6: For Loop
print("Counting from 1 to 5:")
for i in range(1, 6):
    print(i)

# Task 7: While Loop
counter = 0
while counter < 5:
    print("Counter is:", counter)
    counter += 1

# Task 8: Functions
def greet_user(name):
    return f"Hello, {name}!"

print(greet_user("Baysaa"))

# Task 9: List Manipulation
colors = ["red", "blue", "green"]
print("Colors list:", colors)
colors.append("yellow")
print("Updated colors list:", colors)
