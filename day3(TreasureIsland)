print(r'''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\ ` . "-._ /_______________|_______
|                   | |o ;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")

choice1 = input("Which way do you want to go? (left/right)").lower()

if choice1 == "right":
    print("You fell into a hole, game over!")
elif choice1 == "left":
    choice2 = input('You\'ve come to a lake '
                    'There is an island in the middle of the lake.'
                    'Type "swim" to swim across '
                    'Type "wait" to wait for a boat').lower()
    if choice2 == "wait":
        choice3 = input('You arrive at the island unharmed,'
                        'There are 3 door to choose from '
                        'Red,blue or yellow '
                        'Which do you choose?').lower()
        if choice3 == "red":
            print("You got burned by fire, game over!")
        elif choice3 == "blue":
            print("You got eaten by beasts, game over!")
        elif choice3 == "yellow":
            print("Congratulations!, you found the teasure and have won the game.")
    else:
        print("You got attacked by a trout, game over!")