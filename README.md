# Othello (Reversi) – Java Console Game

## Academic Integrity policy
This program was written for University of Toronto's CSC207 course. In accordance to their academic integrity policy, I cannot openly share any implementation details on this repository. I will be, however, open to discuss the project in an interview setting.

## Overview

This project is a **fully integrated console-based implementation of the classic game Othello (Reversi)** written in Java.  
It demonstrates object-oriented programming principles as taught in **CSC207**: inheritance, polymorphism, abstraction, encapsulation.

The game supports **multiple player configurations**, enforces all standard Othello rules, and allows for automated gameplay simulations between computer-controlled players.

---

## Features

- Classic **8×8 Othello board**
- **Legal move enforcement**
- Automatic **disc flipping** in all valid directions
- **Score tracking** throughout the game
- Multiple gameplay modes:
  - Human vs Human
  - Human vs Computer
  - Computer vs Computer (runs simulations)
- Different computer player strategies:
  - Random
  - Greedy
- Fully **console-based interface**
- Follows the exact same rules as that of classical Othello.

---
## Player Modes

- **Human Player**
  - Inputs their desired row and column via console inputs.
- **Computer Player**
  - Random strategy: selects a legal move uniformly at **random**
  - Greedy strategy: selects a legal move that **maximizes** token flips.
---
## Computer vs Computer simulations

### Simulation info:
There are two different simulations, running 10,000 games on random vs random and random vs greedy each.

### Simulation observations:
At the end of each simulation, the win probability was outputted on a scale of 0 to 1 (with 1 meaning 100% win probability). 
The results were as follows:
#### Random vs Random:
* **P1 wins**: 0.4514
* **P2 wins**: 0.5486

#### Random vs Greedy:
* **P1 wins**: 0.3839
* **P2 wins**: 0.6161

---
## Testing
* Unit tests check move legality from human input, token flipping, win/lose conditions, and edge cases for scoring.
* Tests legality of moves made by random and greedy algorithms, tests correctness of helper functions for the algorithms.
