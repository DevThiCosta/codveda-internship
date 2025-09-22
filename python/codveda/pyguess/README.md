# 🎮 PyGuess

PyGuess is a simple command-line number guessing game written in Python.  
The program generates a random number between 1 and 100, and the player must guess it.

---

## 🚀 Features
- Random number generation between 1–100
- Feedback on guesses (too high / too low)
- Attempt counter
- Difficulty levels
- Replay option
- Modular code structure
- Unit tests with `pytest`

---

## 🛠️ Requirements
- Python 3.x
- No external libraries required

---

## ▶️ How to Play
1. When the game starts, you are welcomed and prompted for your guess.
2. Enter an integer between 1 and 100.
3. The game continues until you guess the correct number.
4. A success message is displayed when you win.

---

## 💻 Running the Game
Clone or download the repository and navigate to the `pyguess` directory:

```bash
git clone git@github.com:DevThiCosta/portfolio-projects.git
cd portfolio-projects/pyguess
python -m pyguess.game
