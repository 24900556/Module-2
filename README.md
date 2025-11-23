# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the input into binary using built-in-function.

## 🧠 Algorithm
1.Start

2.Prompt the user to enter a number.

3.Read the input from the user.

4.Convert the input string to an integer.

5.Use the built-in bin() function to convert the integer to a binary string.

6.Print the binary string.

7.End
## 🧾 Program
``` python
x=int(input())
print(bin(x))
```

## Output

![image](https://github.com/user-attachments/assets/fa2829d9-c173-4bb8-871f-79a23f81b3cf)

## Result
Thus the python program to convert the input into binary using built in function is executed successfuly.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts three values and return the average.

## 🧠 Algorithm
1.Start

2.Define a function result(a, b, c) that:

3.Calculates (a + b + c) / 3

4.Returns the result

5.Prompt user to input a, b, and c

6.Convert inputs to integers

7.Call the result function with a, b, and c as arguments

8.Print the returned average

9.End
## 🧾 Program
```python
def result(a,b,c):
    return (a+b+c)/3
a=int(input())
b=int(input())
c=int(input())
print("average is",result(a,b,c))

```
## Output
![image](https://github.com/user-attachments/assets/174d9874-c370-4de1-8beb-a8cb865a2826)

## Result
Thus the Python program that defines a function which accepts three values and return the average is executed successfully

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes z as a parameter and returns z*45 .

## 🧠 Algorithm
1. Get a integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `z*45
3. Call the function with the user inputs and print the result.

## 🧾 Program
``` python
z=int(input())
f=lambda z:z*45
print(f(z))
```
## Output
![image](https://github.com/user-attachments/assets/071447c4-9e85-4fc3-8c40-89b0fee90c1c)

## Result
Thus the python program which takes z as a parameter and returns z*45 is executed successfully.
# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1.Start

2.Read an integer n from the user

3.Repeat for i from 0 to n-1:

4.Repeat for j from i to n-1:

5.Print the value of n followed by a space, staying on the same line

6.Print a newline character after the inner loop

7.End program.


## 🧪 Program
```python
n=int(input())
for i in range(0,n):
    for j in range(i,n):
        print(n,"",end="")
    print()

```
## Sample Output
![image](https://github.com/user-attachments/assets/a1cf7bed-c40b-427d-85d4-fa0c8669b9c0)

## Result
Thus the Python program that generates **Pascal's Triangle** using numbers is executed successfully.
## Loops in Python: Palindrome Number Checker

## 🎯 Aim

To wite a python program to check whether the given number is palindrome or not.


## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `count` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `count = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `count` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
``` pyhton
num=int(input())
temp = num
count =0
while num>0:
    digit =num%10
    count= count*10+digit
    num//=10
if temp== count:
    print("The given number {} is a Palindrome".format(temp))
else:
    print("The given number {} is not a palindrome".format(temp))

```
## Output
![image](https://github.com/user-attachments/assets/22de3a79-e3f0-49d3-be73-abf300a65928)

## Result
Thus python program to check whether the given number is palindrome or not is executed successfully.
