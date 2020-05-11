---
title: Ghost Game
category: share coding
order: 1
---
==#Ghost Game
from random import randint
print('Ghost Game')
feeling_brave = True
score = 0
while feeling_brave:
    ghost_door = randint(1,3)
    print('Three doors ahead...')
    print('One door has a ghost inside')
    print('which door do you open?')
    door = input('1,2,or 3?')
    door_num = int(door)
    if door_num == ghost_door:
         print('GHOST!')
         feeling_brave = False
    else:
         print('No ghost!')
         print('You enter the next room!')
         score = score + 1
print('Run away!')
print('GAME OVER!You scored',score)==

  
  
You can open it on python!
That its!