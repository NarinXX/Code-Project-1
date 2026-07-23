# Code-Project-1
A simple Python program that checks if a user is tall enough to ride a rollercoaster and calculates the ticket price based on age.

print("Welcome to the Rollercoaster!")
height = int(input("Enter your height in cm? "))

if height >= 120:
    print("You can ride the Rollercoaster! :-) ")
    age = int(input("Enter your age? "))
    if age <= 12:
        print("You have to pay $5.99")
    elif age <= 18:
        print("You have to pay $7.99")
    else:
        print("You have to pay $9.99")
else:
    print("Sorry you have to grow taller before you can ride. :-( ")
