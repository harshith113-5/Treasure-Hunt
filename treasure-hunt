import random

# Define a list of locations where the treasure can be hidden
locations = ["forest", "cave", "beach", "mountain", "desert"]

# Randomly select a location to hide the treasure
treasure_location = random.choice(locations)

# Introduction
print("Welcome to the Treasure Hunt Game!")
print("You need to find the hidden treasure in one of these locations:")
print(", ".join(locations))

# Main game loop
while True:
    # Ask the player to enter their guess
    guess = input("Enter your guess: ").lower()

    # Check if the guess matches the treasure location
    if guess == treasure_location:
        print("Congratulations! You found the treasure in the", treasure_location)
        break
    else:
        print("Sorry, the treasure is not in the", guess)
