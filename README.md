# IF,ELIF,ELSE STATEMENT
# 1) check if a number is positive 

num = int(input("Enter a number:"))
if num > 0:
   print("number is positive")
elif num == 0:
  print("number is zero")
else:
   print("number is negative")

# 2) check if number is even or odd

 num = int(input("Enter The Number:"))
 if num % 2 == 0:
   print("number is even")
 else:
   print("number is odd")

# 3) check if a person can vote

 person = int(input("Enter your age:"))
 if person >= 18:
   print("person can vote")
 else:
   print("person can not vote")
# 4) determine the largest of three number

 a = 19
 b = 44
 c = 45
 if a > b and a > c:
   print(a, "is the largest number")
 elif b > a and b > c: 
   print(b, "is the largest number")
 elif c > a and c > b: 
   print(c, "is the largest number")
 else:
   print("all numbers are equal")
# 5) check if a number is divisible by anothe number

 numerator = int(input("Enter the numerator:"))
 denominator = int(input("Enter the denominator:"))
 if denominator != 0 and numerator % denominator == 0:
   print(f"{numerator} is divisible by {denominator}")
 elif denominator == 0:
   print("not defined")
 else:
   print(f"{numerator} is not divisible by {denominator}")
# 6) pass or fail bassed on marks

 marks = int(input("Enter your marks:"))
 if marks >= 35:
   print("you are pass")
 else:
   print("you are fail") 
# 7) check multiple of number

 num1 = int(input("Enter the number:"))
 num2 = int(input("Enter the number:"))
 if num1 % num2 == 0: 
   print(f"multiple of {num2}")
 elif num2 % num1 == 0:
   print(f"multiple of {num1}")
 else:
   print("not multiple")
# 8) compare with another number

 comp = int(input("Enter the number:"))
 if comp > 50:
   print(f"{comp} is greater than 5o")
 elif comp == 50:
   print(f"{comp} is equal to 50")
 else:
   print(f"{comp} is lesser than 50")
# 9) check True or False 

 is_hot = False
 if is_hot:
   print("it is hot day")
   print("drink plenty of water")
 else:
   print("it is cold day")
   print("wear warm clothes")
# 10) take user input True or False

 user = input("Enter True or False:")
 if user == "True":
   print("are you made")
   print("yes")
 else:
   print("you are honest")
# 11) check either condition is true or false

 is_weekend = False
 is_holiday = False
 if is_weekend or is_holiday:
   print("day off")
 else:
   print("working day")

# 12) check condition

 has_pass = True
 has_marks = int(input("Enter your marks:"))
 if has_pass and has_marks >= 35:
   print("you are pass")
 else:
   print("you are fail")

 
