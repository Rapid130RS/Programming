# Question 1
response = int(input ("Enter Number"))
average = 0
sum = 0
if response > 0:
    print("This is a positive number")
    for num in range (0, response+1,1):
      sum = sum+num
    print(sum)
else:
    print("Negative number")
# Question 2
n = input("Enter Number to calculate sum")
n = int (n)
average = 0
sum = 0
for num in range(0,n+1,1):
    sum = sum+num
print("SUM of first ", n, "numbers is: ", sum )
