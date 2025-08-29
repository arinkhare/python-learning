import random
number = random.randint(1, 10)
guess = int(input("Guess a number (1–10): "))
if guess == number:
  print("You got it!")
else:
  print("Wrong! It was", number)
