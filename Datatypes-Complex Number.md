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
```
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))
x = complex(a, b)
print("Complex number:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
```

## Output
```
Enter real part: 3
Enter imaginary part: 4
Complex number: (3+4j)
Real part: 3.0
Imaginary part: 4.0
```

## Result

 A Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts is verified.
