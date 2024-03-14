import random
user_hand=int(input('enter rock=0,paper=1,scissors=2: '))
computer_hand=random.randint(0,2)
if user_hand>2 or user_hand<0:
    print('invalid input so user lose')
else:
    print('computer chose:',computer_hand)
    if user_hand== computer_hand:
        print('its a draw')
    elif user_hand==2 and computer_hand==0:
        print('user lose')
    elif user_hand==0 and computer_hand==2:
        print('user wins')
    elif user_hand> computer_hand:
        print('user wins')
    elif user_hand< computer_hand:
        print('user lose')# rockpaperscissors
