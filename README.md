🎯 Number Guessing Game in C

A simple and interactive **number guessing game** written in **C**, where the computer randomly selects a number between **1 and 100**, and the player tries to guess it with helpful hints along the way.

---

## 📌 Features

- Random number generation using `rand()` and `srand()`
- User-friendly hints:
  - 📉 **"Lower number please!"**
  - 📈 **"Higher number please!"**
- Counts the total number of guesses
- Simple and beginner-friendly logic
- Console-based interactive gameplay

---

## 🛠️ Technologies Used

- **Language:** C
- **Libraries:**
  - `stdio.h` – Input & Output
  - `stdlib.h` – Random number generation
  - `time.h` – Seed for randomness

---

## 🚀 How the Game Works

1. The program generates a **random number between 1 and 100**.
2. The user keeps guessing the number.
3. After each guess:
   - The program tells whether the guess is **too high** or **too low**.
4. The game continues until the correct number is guessed.
5. Finally, the program displays the **total number of attempts** taken.

---

## ▶️ How to Run the Program

### 🔹 Compile
```bash
gcc guessing_game.c -o guessing_game
🔹 Run
bash
Copy code
./guessing_game
📷 Sample Output
text
Copy code
Guess the number: 45
Higher number please!

Guess the number: 78
Lower number please!

Guess the number: 63
Congrats!!
You guessed the number in 3 guesses
🧠 Concepts Used
do-while loop

Conditional statements (if-else)

Random number generation

User input handling

Loop termination conditions

🌱 Possible Improvements
Add difficulty levels (Easy / Medium / Hard)

Limit the number of guesses

Show best score (minimum attempts)

Add replay option

Improve UI messages

👨‍💻 Author
Mohit
Learning C, C++, and Python step-by-step 🚀
Building logic one program at a time.

