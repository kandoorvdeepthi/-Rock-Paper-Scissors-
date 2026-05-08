# -Rock-Paper-Scissors-
This is a functional, command-line version of the classic Rock Paper Scissors game implemented in Python. The game features emoji support and a modular design for easy reading and expansion.

How to Play
1. Run the script: Start the game using your Python interpreter.
2. Make your move: Enter r for Rock, p for Paper, or s for Scissors when prompted.
3. View Results: The computer will reveal its random choice, and the winner is determined based on standard rules.
4. Keep Playing: Decide whether to go another round or exit the game.

Core Features
1. Emoji Integration: Uses visual icons (🪨, 📄, ✂️) to make the console output more engaging.
2. Modular Code Structure: Organized into specific functions for getting choices, displaying results, and determining the winner.
3. Input Validation: A robust loop ensures the game only proceeds with valid user inputs.
4. Randomized AI: Uses the random.choice method to select the computer's move from a tuple of available options.

Technical Details
1. Constants: Key game moves are defined as constants (ROCK, PAPER, SCISSORS) to prevent hardcoding errors.
2. Data Structures: Utilizes a dictionary for emoji mapping and a tuple for valid move choices.

Installation & Execution
1. Save the code into a file named rps.py.
2. Navigate to the file location in your terminal.
3. Execute the script:

Bash = "python rps.py"

Game Rules
1. Rock beats Scissors
2. Scissors beats Paper
3. Paper beats Rock
4. Identical choices result in a Tie
