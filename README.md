# Mastermind-Game
Mastermind game implementation using Python's turtle framework.

Problem:
Create a playable Mastermind game where the user competes against the computer. Mastermind is a code breaking game, where the user tries to guess the correct sequence of four independent colors. This is out of six total colors. The game should take your inputted guess and if the guess is not correct, the game should return the appropriate visual clues. The game should also have a leaderboard that is read in from a text file. Leaderboard based on the lowest number of guesses to crack the code.

Approach:
Game was constructed using Python's turtle framework. Turtle allows for basic event handling along with simple visualizations. The framework was organized using the MVC design pattern. Additional classes for FileIO and various display based objects also incorporated into the program.

Challenges:
This was my first object oriented design project using the MVC design pattern. Thus, I spent a lot of time refactoring code to ensure low-coupling and high-coehesion that is inherent to MVC design. In addition, it was also challenging to create and maintain the significant number of turtle generated objects across the program. This entailed creating multiple structures to hold, modify and return the various objects needed to run the game.

Technologies:
Python, Object Oriented Design, MVC Design Pattern, FileIO, Event Handling

Results:
An operating game that answers all components of the problem statement. Game is also replayable at the user's request. Please see attached photos of the game in operation!

