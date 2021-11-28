import random
import time
r1 = random.randint(0,9999)
r2 = random.randint(0,999)
#r1 = 1
#r2 = 2
name = input('Enter your name----')

print('BEST OF LUCK 👍👍',name)

    
time.sleep(2)


print('FUN MATH GAME ===================================================')
print('                                                           by -------Amritesh Das')
print('Time====10s')
print('                                                                       ')
print('                                                                       ')
time.sleep(2)
print('after 10 s ENTER opsen will apper')
print('                                                                       ')
print('                                                                       ')
time.sleep(2)
print('SoLvE ThE MaTh_____ ')
print('                                                                       ')
print('                                                                       ')


print('➡️                    ',r1,'+',r2)
print('--------------------YoUr TiMe Is StArT-----------------------')



time.sleep(10)
print('STOP!!')

ans = int(input('Enter Your Answer'))

sum = int(r1+r2)




if (ans == sum):
    print('You win the game🏆🏆🏆')

else:
    print('Your Loss The Game😭😭')
