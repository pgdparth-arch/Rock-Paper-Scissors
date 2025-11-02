import random
import time

sign=["Rock","Paper","Scissors"]
score={"Computer":0,"Me":0}
dictio={1:"Rock",2:"Paper",3:"Scissors"}

print("Press 1 for Rock")
print("Press 2 for Paper")
print("Press 3 for Scissors\n")

rounds=int(input("How many rounds you want to play?\n"))

for i in range(rounds):
    opp=random.choice(sign)
    me=int(input("Your choice--"))
    me_choice=dictio[me]
    print (f"Computer chose {opp}")
    
    if opp == me_choice:
        time.sleep(1)
        print("Draw")
    elif (me_choice == "Rock" and opp == "Scissors") or \
         (me_choice == "Paper" and opp == "Rock") or \
         (me_choice == "Scissors" and opp == "Paper"):
        time.sleep(1)
        print("You win this round!")
        score["Me"] += 1
    elif (me_choice == "Rock" and opp == "Paper") or \
         (me_choice == "Paper" and opp == "Scissors") or \
         (me_choice == "Scissors" and opp == "Rock"):
        time.sleep(1)
        print("Computer wins this round!")
        score["Computer"] += 1
print(score)
