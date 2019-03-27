# Programming
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
