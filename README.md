# Missionary_and_Cannibals
Python game
# Missionaries and Cannibals Game

## Overview

This project implements a text-based version of the "Missionaries and Cannibals" puzzle. The puzzle involves transporting missionaries and cannibals across a river using a boat. The challenge is to move the characters from the left bank to the right bank without violating certain rules.

## Rules

1. The boat can only carry a maximum of two individuals at a time.
2. Missionaries and cannibals must be transported without the cannibals outnumbering the missionaries on either side of the river.
3. The game starts with three missionaries and three cannibals on the right bank, and the goal is to move them to the left bank.

## How to Play

1. Run the script.
2. Enter the number of missionaries and cannibals to move to the other side.
3. To quit the game, enter 10.
4. Follow the on-screen instructions and messages.

## Game State Representation

- `boat_side`: Indicates the current side of the river where the boat is ('Right' or 'Left').
- `missionaries_on_right`, `cannibals_on_right`: Number of missionaries and cannibals on the right bank.
- `missionaries_on_left`, `cannibals_on_left`: Number of missionaries and cannibals on the left bank.

The game state is displayed graphically after each move.

## Example

M= 3 C= 3 |-----B| M= 0 C= 0
No of missionaries or enter 10 to quit : 1
No of cannibals : 1
M= 1 C= 1 |B-----| M= 2 C= 2
...
You win


## Winning and Losing

The game ends when the player successfully moves all three missionaries and three cannibals to the left bank or when the missionaries are outnumbered by cannibals on either side of the river, leading to a loss.

## Exiting the Game

To quit the game, enter 10 when prompted for the number of missionaries.

## Note

Ensure that the total number of missionaries and cannibals moved in each turn is either 1 or 2. Otherwise, the move is considered invalid.

Feel free to contribute, report issues, or suggest improvements to this simple implementation of the "Missionaries and Cannibals" game!
