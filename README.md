# Modern_pizza
print("Welcome to domino's delivery")
a = input("Would you like to order the S, M or L sized pizza ")
if a == "S":   
  bill = 50
  enter = input("Would you like pepperoni with your pizza? Y / N ")
  if enter == "Y": 
    bill += 7
  b = input("Would you like cheese with that? Y / N ")
  if b == "Y":
    bill += 9
  print(f"Your total bill is ${bill}")
elif a == "M":
    bill = 70
    f = input("would you like pepperoni with that? Y / N ")
    if f == "Y":
     bill += 7
    c = input("Would you like chicken added to that? Y / N ")
    if c == "Y":
      bill += 9
      print(f"Your total bill is ${bill}")
elif a == "L":
     bill = 120
     type = input("Would you like pepperoni with that? Y / N ")
     if type == "Y":
      bill += 5
     d = input("Should i include tomatoes? Y / N ")
     if d == "Y":
      bill += 7
      print(f"Your total bill is ${bill}")
print("Thanks for your patronage.")
