import random

rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

game_images = [rock, paper, scissors]

my_input = int(input("What is your choice? Type 0 for Rock, 1 for Paper, 2 for Scissors"))

if my_input <= 2 and my_input >=0:
    print(game_images[my_input])

computer_choice = random.randint(0,2)

print("Computer chose: ")
print(game_images[computer_choice])

if my_input > 2 or my_input < 0:
    print("Invalid input, you lose!")
if my_input == computer_choice:
    print("Its a draw!")
elif my_input > computer_choice:
    print("You win!")
elif my_input == 0 and computer_choice == 2:
    print("You win!")
elif computer_choice > my_input:
    print("You lose!")
elif computer_choice == 0 and my_input == 2:
    print("You lose!")
