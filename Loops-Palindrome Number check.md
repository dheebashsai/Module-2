## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
      num = int(input("Enter a number: "))
      
      temp = num
      rev = 0
      
      while temp > 0:
          rev = (rev * 10) + (temp % 10)
          temp = temp // 10
      
      if rev == num:
          print(f"{num} is a palindrome.")
      else:
          print(f"{num} is not a palindrome.")


## Output
case1:
Enter a number: 121
121 is a palindrome.

case2:
Enter a number: 123
123 is not a palindrome.

## Result
The Program to check whether the number is a palindrome number is executed successfully
