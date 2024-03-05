# Find-Arm-strong-number
n = int(input("Enter any number: "))
r = 0
p = n
while(n!=0):
        a = n%10
        n = n//10
        r = r+a*a*a
if(p==r):
        print("It is a arm strong number.")
else:
        print("It is not a  arm strong number.")
