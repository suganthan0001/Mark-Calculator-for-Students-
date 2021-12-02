a = int(input("Enter your English mark: "))
b = int(input("Enter your Maths mark: "))
c = int(input("Enter your Biology mark: "))
d = int(input("Enter your Chemistry mark: "))
e = int(input("Enter your Physics mark: "))

print("Your total mark = ", a+b+c+d+e)
t = a+b+c+d+e
print("Your percentage = ", t/5)
phy = e/2
che = d/2
print("Your Cutt of for engineering = ", phy+che+b)

if a and b and c and d and e >= 25:
   print("Result = PASS")
else:
   print("Result = FAIL")
