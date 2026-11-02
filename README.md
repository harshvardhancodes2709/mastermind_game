# mastermind_game
A Python-based Mastermind game where players have 10 attempts to guess a randomly generated four-color code using color hints for correct and incorrect positions.

# Mastermind Game 🎮

A command-line version of the classic Mastermind code-breaking game built using Python. The player must guess a randomly generated sequence of four colors within 10 attempts using feedback after each guess.

## Features

- Randomly generates a four-color secret code.
- Supports six different colors: Red, Green, Blue, Yellow, White, and Orange.
- Allows up to 10 attempts to guess the code.
- Provides feedback on correctly positioned colors.
- Identifies correct colors placed in incorrect positions.
- Validates user input to prevent invalid guesses.
- Handles repeated colors correctly.

## How to Play

1. Run the Python program.
2. The game generates a secret code containing four colors.
3. Enter your guess using four color initials separated by spaces.
4. The game provides two hints:
   - **Correct Positions:** Number of colors in the correct position.
   - **Incorrect Positions:** Number of correct colors in the wrong position.
5. Keep guessing until you crack the code or run out of attempts.

## Valid Colors

| Color | Initial |
|---|---|
| Red | R |
| Green | G |
| Blue | B |
| Yellow | Y |
| White | W |
| Orange | O |

## Requirements

- Python 3
- `random` module (built-in)

## Installation

1. Clone this repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <your-project-folder>
   ```

## Usage

Run the following command in your terminal:

```bash
python3 main.py
```

Enter four color initials separated by spaces when prompted.

**Example:**

```text
Welcome to Mastermind!, you have 10 to guess the code...
The valid colors are R G B Y W O

Guess: R G B Y
Correct Positions: 2 | Incorrect Positions: 1
```

## Technologies Used

- Python
- Random module
- Loops and conditional statements
- Lists and dictionaries
- Functions
- Input validation
- Zip function

## License

This project is open-source and available for learning and personal use.
