import random

# Pick a random number
secret = random.randint(1, 100)

print("🎯 Guess the number game!")

guess = -1    #start with anything not equal to secret
#keep looping as long as long as the number is NOT 0
#The game continues until the player guesses corrently.
while guess != secret and guess != 0:
    guess = int(input("Enter a number (1, 100), or 0 to quit: "))

    if guess == 0:
        print("You quit the game. Goodbye!")
        break
    elif guess > secret:
        print("Too high, try again.")
    elif guess < secret:
        print("Too low, try again.")
    else:
        print("You won! The number was", secret)

print("Game Over!")
