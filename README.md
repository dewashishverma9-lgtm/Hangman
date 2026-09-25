# 🎮 Hangman Game — Python

A simple **command-line Hangman game built with Python**. The player has to guess a randomly selected word, one letter at a time, before running out of lives.

This project was built to practice **Python fundamentals, loops, conditionals, lists, functions/modules, user input, and the `random` module**.

## 📌 Features

* 🎲 Randomly selects a word from a word list
* 🔤 Letter-by-letter guessing
* ❤️ 6 lives per game
* 🔁 Tracks correctly guessed letters
* ⚠️ Detects incorrect guesses
* 🏆 Win and lose conditions
* 🎨 ASCII-art Hangman stages
* 💻 Runs directly in the terminal

## 🛠️ Technologies Used

* **Python 3**
* `random` module
* Python lists
* Loops and conditionals
* User input
* Custom Python modules

## 📂 Project Structure

```text
Hangman/
│
├── main.py
├── hangman_words.py
├── hangman_art.py
└── README.md
```

### `main.py`

Contains the main game logic, including:

* Selecting a random word
* Processing guesses
* Tracking lives
* Displaying the current word
* Checking win/lose conditions

### `hangman_words.py`

Contains the list of words used by the game.

### `hangman_art.py`

Contains the Hangman logo and ASCII-art stages displayed during the game.

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the project folder

```bash
cd Hangman
```

### 3. Run the game

```bash
python main.py
```

## 🎯 How to Play

1. Run the program.
2. A random word will be selected.
3. Guess one letter at a time.
4. Correct guesses reveal the letter.
5. Incorrect guesses reduce your lives.
6. Guess the complete word before all 6 lives are lost.

## 🧠 What I Learned

Building this project helped me practice:

* Working with Python lists
* `for` and `while` loops
* `if / elif / else` statements
* User input handling
* String manipulation
* The `random` module
* Importing custom Python modules
* Managing game state with variables
* Building a simple command-line application

## 🔮 Possible Improvements

Future versions could include:

* [ ] Difficulty levels
* [ ] Word categories
* [ ] Score system
* [ ] Multiple rounds
* [ ] Input validation
* [ ] Hint system
* [ ] Replay option
* [ ] Larger word database
* [ ] GUI version using Tkinter or Pygame

## 📸 Example

```text
****************************6/6 LIVES LEFT****************************
Guess a letter: a

Word to guess: _ a _ _ _

****************************5/6 LIVES LEFT****************************
Guess a letter: e

e is not in the word
```

## 👨‍💻 Author

**Dewashish Verma**

Built as part of my journey learning **Python and practical programming**.

---

⭐ If you found this project interesting, feel free to explore the repository and check out my other Python projects.
