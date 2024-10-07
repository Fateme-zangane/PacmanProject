# Pacman Game

This is a simple implementation of the classic Pacman game developed using Python with Pygame and Pillow libraries.

## Features
- Classic Pacman gameplay
- Collectible coins
- Multiple ghosts with AI behavior (A* algorithm)
- Simple user interface
- Sound effects and animations

## Requirements

To run this project, you'll need the following libraries installed:
- pygame
- os , sys
- request 
- datatime
- 

You can install the necessary libraries using pip:
```
pip install pygame pillow

```

## Project Setup 

First, clone this repository:
```
git clone https://github.com/Fateme-zangane/PacmanProject.git
cd PacmanProject
```

Running the Code:
In the terminal run this code:
```
python main.py

```

## GamePlay
Use the arrow keys to move Pacman around the grid.
Collect coins to earn points.
Avoid ghosts; if they touch Pacman, the game is over.

## File Structure 
```
PacmanProject/
├── main.py            # Main code for the Pacman game, handles game logic and user input
└── pacfuncs.py        # Contains functions for initializing the game grid and handling collisions
└── pacstructs.py      # Contains classes for game objects (Pacman, Ghost, GridCell, SearchNode, etc.)
└── info.txt           # Additional information or configuration settings related to the game
└── data               #Have some initial image required for graphical presentation 

└── README.md          # This README file providing an overview and documentation of the project
```


## License

This project is licensed under the MIT License.

## Contact

For any questions, please reach out to me via GitHub.
