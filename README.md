# leap-year
Finding if an year is gonna be a leap year or not.
# Don't change the code below 
year = int(input("Which year do you want to check? "))
#Don't change the code above 

#Write your code below this line 
if year % 4 ==0:
  print("leap year")
else:
  print("not leap year")
  if year % 100 ==0:
    print("not leap year")
  else:
    print("leap year")
    if year % 400 ==0:
      print("leap year")
    else:
      print("not leap year")

