#write a program to prompt the user for hours and rate per hour using input to compute gross pay. pay the hourly rate for the hours up to 40 and 1.5 times the hourly rate for all hours worked above 40 hours. use 45 hours and a rate of 10.50 per hour to test the program (the pay should be 498.75). you should use input to read a string and float() to convert the string to a number. do not worry about error checking the user input - assume the user types numbers properly.


def computepay(h,r):
    if hrs<=40:
        pay= h*r
    elif hrs>40:
        return (40*r+(h-40)*1.5*r)
    return pay
hrs =input("Enter Hours:")
h= float(hrs)
rate= input("Enter Rate:")
r= float(rate)
p = computepay(h,r)
print(p)
