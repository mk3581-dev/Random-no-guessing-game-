# Number Guessing Game in C 🎯

A simple **Number Guessing Game** written in C.  
The computer generates a random number between 1 and 100, and the player has to guess it. The program provides hints whether to guess higher or lower and counts the number of attempts.

---

## Features

- Generates a random number between 1 and 100
- User-friendly hints:
  - "Higher number please!" if your guess is too low
  - "Lower number please!" if your guess is too high
- Counts the number of guesses and displays it at the end
- Written in **C** using `stdio.h`, `stdlib.h`, and `time.h`

---

## How to Play

1. Compile the program using a C compiler:
    ```bash
    gcc number_guessing_game.c -o number_guessing_game
    ```
2. Run the executable:
    ```bash
    ./number_guessing_game
    ```
3. Enter your guesses when prompted.
4. Keep guessing until you find the correct number.
5. The program will tell you how many guesses you took.

---

## Example Output

