# IHR BATTLESHIPS GAME

## Description
**IHR Battleships Game** is a Python terminal-based game that lets users experience naval warfare. Command your fleet, strategically position ships, and engage in intense battles. Showcase your Python skills and enjoy immersive gameplay. Dive into the seas and conquer in Battleship!

This project is hosted on the Heroku Cloud Platform.

View the live project [here](https://ihr-battleship-1147d52d8a23.herokuapp.com/) or by copy & Pasting https://ihr-battleship-1147d52d8a23.herokuapp.com/ 

![Game Screenshot](https://hasibullah.com/da/01.PNG)

## How to Play
IHR Battleships Game is based on the classic pen-and-paper game. You can read more about it on [Wikipedia](https://en.wikipedia.org/wiki/Battleship_(game)).

In this version, the player enters their name, and two boards are randomly generated:
- The player can see where their ships are, indicated by an '@' sign, but cannot see where the computer's ships are.
- Guesses are marked on the board with an 'X'. Hits are indicated by '*'.
- The player and the computer then take turns to make guesses and try to sink each other's battleships.
- The winner is the player who sinks all of the opponent's battleships first.

### Features

#### Existing Features
- Random board generation
  - Ships are randomly placed on both the player and computer boards.
  - The player cannot see where the computer's ships are.
  
![Random Board Generation](https://hasibullah.com/da/02.PNG)

- Play against the computer
- Accepts user input
- Maintains scores

![Gameplay](https://hasibullah.com/da/03.PNG)

- Input validation and error-checking
  - You cannot enter coordinates outside the size of the grid.
  - You must enter numbers.
  - You cannot enter the same guess twice.

![Input Validation](https://hasibullah.com/da/04.PNG)

## Data Model
I decided to use the `Player` class as my model. The game creates two instances of the `Player` class to hold the player's and the computer's boards. The `player` class stores the board size, the number of ships, the position of ships, and the guesses against that board.

## Testing
I have manually tested this project by doing the following:
- Passed the code through a PEP8 Linter and confirmed there are no problems.
- Given invalid inputs: strings when numbers are expected, out-of-bound inputs, and the same input twice.
- Tested in my local terminal and the Code Institute Heroku terminal.

![Testing](https://hasibullah.com/da/05.PNG)

### Bugs
No bugs were found.

### Remaining Bugs
No bugs remain.

#### Validator Testing
- PEP8: No errors were returned from PEP8.

## Deployment
This project was deployed using the Heroku Cloud Platform.

Steps for deployment:
1. Fork or clone this repository.
2. Create a new Heroku app.
3. Set the buildbacks to Python and NodeJS in that order.
4. Connect to GitHub using your username and password.
5. Link the Heroku app to the repository.
6. Click on deploy.

## Credits
- Code Institute
- Wikipedia
- Heroku for deployment
