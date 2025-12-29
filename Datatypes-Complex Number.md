# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))

x = complex(a, b)

print("Complex number x:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)

## Output
<img width="417" height="268" alt="image" src="https://github.com/user-attachments/assets/21fc19c6-f19a-4403-9186-e79f27eea7d1" />

## Result
Thus,the program is executed successfully
