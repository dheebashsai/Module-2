# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

f = lambda x, y: x + y

print("The sum is:", f(a, b))

## Output
Enter the first number: 15
Enter the second number: 25
The sum is: 40


## Result
The program to add two numbers using lambda function is executed successfully
