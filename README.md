# Project1
#Find Number 
#Import random
from random import randint
#Create value random number
comp_find_number=randint(0,10)
#Start game
play=True
while play:
    num=int(input("Please write number !!!"))
    if num==comp_find_number:
        play=False
        print("You win!!! ")
    if num > comp_find_number:
        print("The computer has memorized a larger number")
    if num < comp_find_number:
        print("The computer has memorized a larger number")
    


