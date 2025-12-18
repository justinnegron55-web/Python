import random
options = ["rock", "paper", "scissors"]

print("Welcome to Rock Paper Scissors!")
while True:
    user = input("Choose rock, paper, or scissors (or 'quit' to stop): ").lower()
    
    if user == "quit":
        print("Game over!")
        break

    if user not in options:
        print("Invalid choice. Try again!")
        continue

    computer = random.choice(options)
    print("Computer chose:", computer)

    if user == computer:
        print("It's a tie!\n")
    elif (user == "rock" and computer == "scissors") or \
         (user == "paper" and computer == "rock") or \
         (user == "scissors" and computer == "paper"):
        print("🎉 You win!\n")
    else:
        print("❌ You lose!\n")
