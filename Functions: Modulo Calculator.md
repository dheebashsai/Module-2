# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
    def result(a, b):
        mod = a % b
        print("The result of", a, "%", b, "is:", mod)
    
    
    num1 = int(input("Enter the first number: "))
    num2 = int(input("Enter the second number: "))
    
    result(num1, num2)

## Output
Enter the first number: 29
Enter the second number: 5
The result of 29 % 5 is: 4


## Result
The program for Modulo calculator is executed successfully
