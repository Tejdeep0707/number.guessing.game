import random

def guess_number_game():
    number_to_guess = random.randint(1, 100)
    attempts = 0
    max_attempts = 5

    print("Welcome to the Number Guessing Game!")
    print("I'm thinking of a number between 1 and 100.")
    print(f"You have {max_attempts} attempts to guess the correct number.\n")

    while attempts < max_attempts:
        guess = int(input(f"Attempt {attempts + 1}: Make a guess: "))
        attempts += 1

        if guess < number_to_guess:
            print("Too low!")
        elif guess > number_to_guess:
            print("Too high!")
        else:
            print(f"Congratulations! You've guessed the number {number_to_guess} correctly in {attempts} attempts!")
            break

    if attempts == max_attempts and guess != number_to_guess:
        print(f"Sorry! You've used all your attempts. The number was {number_to_guess}.")

