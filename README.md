wallet = 100
import random
goal = random.randint (1,10)
while wallet >= 0:
    gusse = int(input('what is the number:'))
    if gusse == goal:
        wallet +=10 
        print ('coerect you have',wallet,'in your wallet')
        break
    else:
        wallet -=10 
        print('you lost 10 dolars you have',wallet,'left')
    if wallet == 0:
        print('you dont have mony')
