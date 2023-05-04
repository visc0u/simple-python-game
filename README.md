# simple-python-game
import random
l=["snake","water","gun"]
while True:
    user=input("enter your choice: ")
    a=random.choice(l)
    if user==a:
        print("draw")
        print("play again")
    elif user=="snake" and a=="water" or user=="water" and a=="gun" or user=="gun" and a=="snake":
        print("YOU WON!!!")
        print("Play again!!!")
    else:
        print("YOU LOOSE!!!")
        print("Play Again!!!")
