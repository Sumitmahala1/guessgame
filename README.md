 # guessgame
 number = 7 # The secret number
guess = 0
while guess != number:
    guess = int(input("Guess the number (1-10): "))
    if guess == number:
        print("Correct! You won!")
    elif guess < number:
        print("Too low, try again")
    else:
        print("Too high, try again")    
