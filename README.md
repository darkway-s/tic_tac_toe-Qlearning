# tic_tac_toe-Qlearning

RL on tic tac toe game

## Goal

Use Q-Learning to create a program that can play Tic-Tac-Toe with a human player.

The optimal policy should be able to directly replace the RandomPolicy in the two main scripts, and good enough to win human player (if a human player makes mistake) or draw every time.
Usage

## how to run

To run the game with an agent using random policy, which chooses a random available position, and put mark there. run
```
python main.py
```
for a terminal interface, or
```
python main_gui.py
```
and select Random as your opponent for a graphic interface. You will need the PyQt5 library to support it. To install it, run
```
pip install PyQt5
```
After you have finished the q-learning policy, you can run
```
python main.py -p QLearningPolicy
```
 or run
```
python main_gui.py
```
and select QLearning as your opponent for the graphic interface. 
