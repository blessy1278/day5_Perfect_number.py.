# day5_Perfect_number.py.
num=int(input("Enter a number"))
sum=0
for i in range(1,num):
  if num%i==0:
    sum=sum+i
if sum==num:
  print("The given number is a Perfect Number")
else:
  print("The given number is not a perfect number")
