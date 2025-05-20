# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
    a = 16
    binary = bin(a)
    print("Binary representation of", a, "is", binary)


## Output
![Screenshot 2025-05-19 202906](https://github.com/user-attachments/assets/c1013503-303c-4191-8680-59a145aaa016)

## Result
Thus, the program is verified successfully.

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
        print("Result of modulo:", mod)
    num1 = int(input("Enter first integer: "))
    num2 = int(input("Enter second integer: "))
    result(num1, num2)


## Output
![Screenshot 2025-05-19 203122](https://github.com/user-attachments/assets/ddd27370-b5bc-4434-81e3-0e39d62cda9a)

## Result
Thus, the program is verified successfully.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
      import math
      rows = int(input("Enter the number of rows: "))
      for n in range(rows):
          print(" " * (rows - n), end="")
          for k in range(n + 1):
              value = math.factorial(n) // (math.factorial(k) * math.factorial(n - k))
              print(value, end=" ")
          print()  

## Sample Output
![Screenshot 2025-05-19 203510](https://github.com/user-attachments/assets/0033b6f3-a7cc-451b-9c74-fc648a7f77e6)

## Result
Thus, the program is verified successfully.

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
          rev = (10 * rev) + (temp % 10)
          temp = temp // 10
      if rev == num:
          print(num, "is a palindrome.")
      else:
          print(num, "is not a palindrome.")

## Output
![Screenshot 2025-05-19 203755](https://github.com/user-attachments/assets/b7b92375-03fd-4f14-ba5d-4a6a203e388d)

## Result
Thus, the program is verified successfully.
