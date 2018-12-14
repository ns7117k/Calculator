# Calculator

# This function adds three numbers together
def add(x, y, z):
   return x + y + z

# This function subtracts three numbers together 
def subtract(x, y, z):
   return x - y - z


print("Select Add or Subtract.")
print("1.Add")
print("2.Subtract")


# Take input from the user 
choice = input("Enter choice(1/2/3/4):")

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
num3 = int(input("Enter third number: "))

if choice == '1':
   print(num1,"+",num2,"+",num3,"=", add(num1,num2,num3))

elif choice == '2':
   print(num1,"-",num2,"-",num3,"=", add(num1,num2,num3)
