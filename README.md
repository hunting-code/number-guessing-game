# 🎯 Number Guessing Game

A fun command-line game built with Python where the computer picks a secret number and you have to guess it!
This is my **Project 01** from my Python learning roadmap — built to learn the core concepts of Python programming.

---

## 🎮 How to Play

1. Enter your name
2. Choose a difficulty level — Easy, Medium, or Hard
3. Guess the secret number within the allowed attempts
4. Get hints after every guess — "Too High" or "Too Low"
5. Score points based on how fast you guess!

---

## 🚀 Features

- 3 difficulty levels (Easy / Medium / Hard)
- Smart hints — tells you if you're "close" or "far off"
- Score system based on attempts used and difficulty
- Play again option after each round
- Input validation — handles wrong inputs gracefully

---

## 💡 What I Learned Building This

| Concept | How I used it |
|---|---|
| Variables | Storing the secret number, player name, score |
| If / Elif / Else | Checking if guess is too high, too low, or correct |
| While loops | Keeping the game running until guesses run out |
| Functions | `play_game()` and `calculate_score()` |
| Dictionaries | Storing difficulty settings |
| Random module | Generating the secret number |
| Error handling | Try/except to handle non-number inputs |

---

## 🛠️ How to Run

Make sure you have **Python 3.10+** installed. Then:

```bash
# Clone this repository
git clone https://github.com/YOUR_USERNAME/number-guessing-game.git

# Move into the folder
cd number-guessing-game

# Run the game
python number_guessing_game.py
```

No extra libraries needed — runs on pure Python!

---

## 📸 Sample Output

```
=============================================
   WELCOME TO THE NUMBER GUESSING GAME!
=============================================

What's your name? Aryan

Hello, Aryan! Let's play.

Choose a difficulty:
  [easy]    Easy   (1–50,  10 guesses)
  [medium]  Medium (1–100,  7 guesses)
  [hard]    Hard   (1–200,  5 guesses)

Your choice: medium

I've picked a number between 1 and 100.
You have 7 guesses. Good luck!

Guesses remaining: 7
Guess a number (1–100): 50
⬆️  Too low! Go higher.

Guesses remaining: 6
Guess a number (1–100): 75
⬇️  So close! A little lower.

Guesses remaining: 5
Guess a number (1–100): 73
🎉  YES! The number was 73!
    You got it in 3 guesses.
    Score: 90 points
```

---

## 📁 Project Structure

```
number-guessing-game/
│
├── number_guessing_game.py   # Main game file
└── README.md                 # You are here
```

---

## 🗺️ My Python Learning Roadmap

This is part of a series of projects I am building to learn Python from scratch:

- [x] **Project 01** — Number Guessing Game ← You are here
- [ ] **Project 02** — Personal Expense Tracker
- [ ] **Project 03** — File Organizer Bot
- [ ] **Project 04** — Daily Reminder Bot
- [ ] **Project 05** — Cricket Score Tracker
- [ ] **Project 06** — Stock Price Dashboard
- [ ] **Project 07** — Resume / PDF Parser
- [ ] **Project 08** — News Summarizer with AI
- [ ] **Project 09** — Personal Finance Dashboard

---

## 👤 Author

**Your Name**
- GitHub: [@your_username](https://github.com/your_username)
- Learning Python — one project at a time 🐍

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with Python 3 | Part of my coding journey 🚀*
