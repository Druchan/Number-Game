# Number-Game
A Simple Number Game using JAVA 

---

# Number Game

Welcome to the Number Game! This is a simple console-based game where the player tries to guess a randomly generated number between 1 and 100. The player has a limited number of attempts to guess the correct number, and the game can be played for multiple rounds.

## How to Play

1. The computer will generate a random number between 1 and 100.
2. You have 5 attempts to guess the correct number.
3. After each guess, you will be told whether your guess is too high or too low.
4. If you guess the number correctly, you will be informed of your success and the number of attempts you took.
5. If you do not guess the number within 5 attempts, the correct number will be revealed.
6. You can choose to play another round or end the game after each round.

## Scoring

- You gain points based on the number of attempts you take to guess the correct number.
- The score for each round is calculated as `5 - number of attempts + 1`.
- Your total score is the sum of scores from all rounds.

## Usage

To run the game, compile and execute the `NumberGame` class.

### Compilation

```bash
javac NumberGame.java
```

### Execution

```bash
java NumberGame
```

## Code Overview

The main components of the code are as follows:

- **Random Number Generation:** Uses `Random` class to generate a number between 1 and 100.
- **User Input:** Uses `Scanner` class to read user guesses from the console.
- **Game Loop:** The game runs in a loop allowing multiple rounds until the player decides to quit.
- **Guess Checking:** Compares user guesses to the random number and provides feedback.
- **Scoring and Rounds:** Tracks the number of rounds played and the score accumulated.

## Example

```
Welcome to the Number Game!
Computer Has Generated Random Numbers Between 1 to 100.
Guess a Number Between 1 to 100. You Have Only 5 chances to Guess.
Enter your guess:
Attempt Number 1:
50
Too low!
Enter your guess:
Attempt Number 2:
75
Too high!
Enter your guess:
Attempt Number 3:
60
Too low!
Enter your guess:
Attempt Number 4:
65
Congratulations! You have guessed it correctly.
Number of attempts you have taken to guess is: 4
Do you want to play another round? (y/n): n
Game Over! You Have played 1 Round, And You've Scored 2.
Thank You For Playing!
```

## Author

- Chandru S

---

