# Roller-coaster-ride
Project 3 Roller coaster ride calc
print("welcome to roller coaster")
h=int(input("enter your height in cm:"))
b=0
if h > 120:
    print("You are eligible to ride")
    a=int(input("enter your age:"))

    if a <+12:
        b+=5
        print("price for kids is 5")
    elif a <=18:
        b+=10
        print("price for youth is 10")
    elif a>=45 and a<=55:
        print("Ride is  on us")
    else:
        b+=15
        print("price for adult is 15")

else:
    print("you are not eligible for ride")

p=input("Do you want a picture for $3?? y for yes n for no")
if p=="y":
    b+=3
else:
    b+=0
print(f"your total is ${b}")
