# tipcalculator
//This code calculates tip using python//
bill=float(input("enter the amount:"))
tip=int(input("enter the tip percentage:"))
a=(tip/bill)
b=(a*100)
c=int(input("enter number of persons:"))
amount=((bill+b)/c)
print(amount)
print("amount to be given:")
d=(round(amount,2))
d="{:.2f}".format(amount)
print(d)
