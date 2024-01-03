Python 3.12.0 (v3.12.0:0fb18b02c8, Oct  2 2023, 09:45:56) [Clang 13.0.0 (clang-1300.0.29.30)] on darwin
Type "help", "copyright", "credits" or "license()" for more information.
>>> # 4.6 Write a program to prompt the user for hours and rate per hour using input to compute gross pay. Pay should be the normal rate for hours up to 40 and time-and-a-half for hourly rate for all hours worked above 40 hours. Put the logic to do the computation of pay in a function called computepay() and use the function to do the computation. The function should return a value. Use 45 hours and a rate of 10.50 per hour to test the program (the pay should be 498.75). You should use input to read a string and float() to convert the string to a number.
>>> def computepay(h, r):
...     if o == '0':
...         return (float(h*r))
...     elif o > '0':
...         return (float(h)*float(r)+float(o)*float(r)*1.5)
... 
...     
>>> h = input("Enter Hours:")
Enter Hours:40
>>> r = input("Enter Rate:")
Enter Rate:10.50
>>> o = input("Enter Overtime Hours:")
Enter Overtime Hours:5
>>> p = computepay(h, r)
>>> print("Pay", p)
Pay 498.75

