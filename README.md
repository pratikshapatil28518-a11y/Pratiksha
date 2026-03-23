# Pratiksha
Assignment 3

1)
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print("Greatest number =", a)
elif b >= a and b >= c:
    print("Greatest number =", b)
else:
    print("Greatest number =", c)


OUTPUT 

Enter first number: 10
Enter second number: 20
Enter third number: 30
Greatest number = 30

2)
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")


OUTPUT 

Enter a number: 25
Odd number

3)
ch = input("Enter a character: ")

if ch.isalpha():
    if ch.isupper():
        print("Uppercase letter")
    else:
        print("Lowercase letter")
else:
    print("Not an alphabet")

OUTPUT 

Enter a character: z
Lowercase letter

4)
ch = input("Enter any input: ")

if ch.isdigit():
    print("It is a number")
else:
    print("It is a character")


OUTPUT 

Enter any input: Pratiksha
It is a character


