Aim

To write a Python program to demonstrate and perform different types of operators such as arithmetic, relational, logical, bitwise, and assignment operators.

Algorithm

1.Start the program.

2.Initialize two variables a and b.

3.Perform arithmetic operations using +, -, *, /, and %.

4.Perform relational operations using <, <=, >, >=, ==, and !=.

5.Perform logical operations using and, or, and not.

6.Perform bitwise operations using &, |, ^, ~, <<, and >>.

7.Perform assignment operations using assignment operators.

8.Display the results of all the operations.

9.Stop the program.
#a = 10
b = 20
code
print("ARITHMETIC OPERATORS")
print("Addition =", a + b)
print("Subtraction =", a - b)
print("Multiplication =", a * b)
print("Division =", a / b)
print("Modulus =", a % b)

print("\nRELATIONAL OPERATORS")
print("a < b =", a < b)
print("a <= b =", a <= b)
print("a > b =", a > b)
print("a >= b =", a >= b)
print("a == b =", a == b)
print("a != b =", a != b)

print("\nLOGICAL OPERATORS")
print("a < b and a > 5 =", a < b and a > 5)
print("a < b or a < 5 =", a < b or a < 5)
print("not(a < b) =", not(a < b))

print("\nBITWISE OPERATORS")
print("a & b =", a & b)
print("a | b =", a | b)
print("a ^ b =", a ^ b)
print("~a =", ~a)
print("a << 1 =", a << 1)
print("a >> 1 =", a >> 1)

print("\nASSIGNMENT OPERATORS")
x = 10
print("x =", x)

x += 5
print("x += 5 =", x)

x -= 3
print("x -= 3 =", x)

x *= 2
print("x *= 2 =", x)

x /= 4
print("x /= 4 =", x)

x %= 3
print("x %= 3 =", x) EXP-1
