# Mastermind
A Recreation of the classic Mastermind created in Python using PyGames Library


Breakdown of Features:

    Color Selection:
        The player selects colors from the row of rectangles at the bottom of the screen.
        Each rectangle corresponds to one of the available colors.

    Submit Button:
        A "Submit Guess" button appears below the color selection area. Once the player selects 4 colors, they can press the button to submit their guess.
        When the player clicks this button, the guess is processed and feedback is given.

    Feedback:
        After each guess, the game provides feedback using black and white pegs.
            Black pegs indicate correct color and position.
            White pegs indicate correct color but wrong position.

    Win Condition:
        If the player correctly guesses the secret code (i.e., receives 4 black pegs), the game declares a win.

    Game Reset:
        You can reset the game at any time by restarting the program.

To Run the Game:

    Make sure Pygame is installed (pip install pygame).
    Run the Python script, and you'll be able to play the Mastermind game where you submit guesses using the "Submit Guess" button.
