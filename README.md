import random

# Generate a random number between 1 and 10
secret_number = random.randint(1, 10)

# Get input from the user
guess = int(input("Guess the number (between 1 and 10): "))

# Check if the guess is correct
if guess == secret_number:
    print("Congratulations! You guessed the correct number.")
else:
    print("Sorry, the correct number was", secret_number)
