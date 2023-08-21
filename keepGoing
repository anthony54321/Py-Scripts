### keepGoing.py
### demonstrates loop with multiple exit

correct = "IndyPy"
tries = 0

keepGoing = True
while(keepGoing):

    tries = tries + 1

    guess = input("What is the password? ")
    if guess == correct:
        print("That's correct!  here's the teasure!")
        keepGoing = False

    elif guess != correct:
        print("ERROR. TRY AGAIN")

        if tries >= 3:
            print("Too many wrong tries. Launching the missiles")
            keepGoing = False
