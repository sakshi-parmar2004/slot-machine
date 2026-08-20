# Python Slot Machine

A simple terminal-based slot machine game built with Python. The game lets the player deposit money, choose a number of lines to play, place a bet, spin the reels, and win based on matching symbols.

## Features

- Deposit and manage a balance
- Choose between 1 and 3 betting lines
- Set a bet amount within the allowed range
- Randomized slot machine spin logic
- Win detection across lines
- Balance update after each spin
- Simple command-line interface

## How It Works

The game uses a 3x3 reel grid and four symbols:

- A
- B
- C
- D

Each symbol has a different frequency and payout value. The script generates a random set of symbols for each column, displays the result, checks whether the selected lines have winning combinations, and updates the player's balance accordingly.

## Project Files

- [main.py](main.py) — main game logic and gameplay loop

## Requirements

- Python 3.x

## Run the Game

From the project directory, run:

```bash
python main.py
```

## Gameplay Flow

1. Enter a starting deposit amount.
2. Press Enter to spin.
3. Choose how many lines to play.
4. Choose a bet per line.
5. The slot machine generates a random result.
6. If you win, the payout is added to your balance.
7. Continue spinning until you quit.

## Example

```text
What would you like to deposit? $50
Current balance is $50
Press enter to play (q to quit).
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $5
You are betting $5 on 2 lines. Total bet is equal to: $10
A | B | C
D | A | A
C | C | B
You won $10.
You won on lines: 1
```

## Notes

This project is intended as a beginner-friendly Python game and is a good example of:

- randomization
- loops and validation
- balance management
- basic game logic
- console UI design

## License

This project is provided for educational purposes.
