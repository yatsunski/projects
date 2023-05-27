# projects
# My projects from 100 Days 
# Day 4
# Game 'rock, paper, scissors'
import random

list_of_game=['rock', 'paper', 'scissors']

X=int(input('Please enter 0(rock) or 1(paper) or 2(scissors) '))

if X!=0 and X!=1 and X!=2:
    print('is wrong number, please try again')
    X = int(input('Pkease enter 0(rock) or 1(paper) or 2(scissors) '))
print(f'your choise is {list_of_game[X]}')
computer=list_of_game[random.randint(0,len(list_of_game)-1)]
print(f'computer choosed {computer}')
if list_of_game[X]==computer:
    print('draw! start over')
    X = int(input('Please enter 0(rock) or 1(paper) or 2(scissors) '))
if computer=='rock' and X==1 or computer=='paper' and X==2 or computer=='scissors' and X==0:
    print('Congratulation! You win the computer!')
if computer=='paper' and X==0 or computer=='scissors' and X==1 or computer=='rock' and X==2:
    print('Sorry, frind! You are looser')
