# Rock,paper, scissor program

import random

def play():
  player = input("\nChoose your move out of 'r' for rock, 'p' for paper and 's' for scissor : ")
  computer = random.choice(['r','p','s'])
  if player == computer :
    print("\nIt's a TIE :)\n")
  elif victory(player,computer):
    print('\nYou WON !!!')
  else:
    print('\nYou LOST !') 

# We know  r > s , s > p , p > r

def victory(player1,player2):
  if (player1 == 'r' and player2 =='s') or (player1 == 's' and player2 =='p') or (player1 == 'p' and player2 =='r') :
    return True

while True:
  wish = input('Do you want to play ? (y/n):')
  if wish.lower() == 'y':
      print(play()) 
  else:
      print ('\n...Thank You...')
      break
