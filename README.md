# Dice Game: Race to 50

This is a **simple dice game** implemented in Python, where 2 to 4 players compete to reach a maximum score of 50. Each player rolls a virtual die to accumulate points, but rolling a `1` ends their turn with no score gained that round.

---

## Features

- Supports 2 to 4 players.
- Players take turns rolling a die.
- Rolling a `1` ends the turn with no points added for that round.
- The first player to reach a total score of **50 or more** wins the game.
- Interactive and beginner-friendly.

---

## How It Works

1. **Player Count Selection**:
   - Users are prompted to enter the number of players (between 2 and 4).

2. **Game Turn**:
   - Each player rolls the die in their turn.
   - The die rolls a random number between `1` and `6`.
   - Rolling a `1` forfeits the points accumulated in that round, and the turn ends.

3. **Winning the Game**:
   - The game continues until a player reaches or exceeds a score of 50.
   - The player with the highest score is declared the winner.

---

## Prerequisites

- Python 3.x installed on your system.

---

## How to Play

1. Clone this repository to your local machine:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Run the game:
```
python pig.py
```

3. Follow the on-screen instructions:

Input the number of players.

Take turns rolling the dice by typing y to roll.

Try to maximize your score without rolling a 1.





---

## Example Gameplay

Enter the number of players (2 - 4): 3

Player number 1 turn has just started!
Your total score is: 0

Would you like to roll (y)? y
You rolled a: 4
Your score is: 4

Would you like to roll (y)? y
You rolled a: 5
Your score is: 9

Would you like to roll (y)? n
Your total score is: 9

Player number 2 turn has just started!
Your total score is: 0

Would you like to roll (y)? y
You rolled a: 1
You rolled a 1! Turn done!
Your total score is: 0

The game continues until one player scores 50 or more. The winner is displayed at the end.


---

## File Structure
```
.
├── dice_game.py       # Main Python script for the dice game
└── README.md          # Documentation file
```

---

## License

This project is open-source and available under the MIT License. You are free to use, modify, and distribute it as per the license terms.


---

Have fun playing and may the dice roll in your favor!



