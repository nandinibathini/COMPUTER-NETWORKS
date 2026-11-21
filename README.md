Prime Number Program in Python

Description:

This Python program checks whether a given number is a prime number or not.

Code:

n = int(input("Enter a number: "))

if n > 1:
    for i in range(2, n):
        if n % i == 0:
            print("Not Prime")
            break
    else:
        print("Prime")
else:
    print("Not Prime")

Output:

Enter a number: 7
Prime

Language

Python
