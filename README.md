# The Mystery Island Adventure Game

Welcome to *The Mystery Island*, an interactive text-based adventure game written in Python. In this game, every decision you make influences your path on the mysterious island. Developed with advanced Python programming techniques, this project is an excellent example of interactive storytelling, dynamic gameplay, and modular design.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Prerequisites & Installation](#prerequisites--installation)
  - [Tech Stack](#teck-stack)
  - [Before running the Game](#before-running-the-game)
- [Usage](#usage)
  - [Input Syntax & Commands](#input-syntax--commands)
  - [Running the Game](#running-the-game)
- [Code Structure](#code-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## About the Project

*The Mystery Island* is an interactive game where choices lead to divergent outcomes – from dangerous encounters with pirates, cannibals, and orcs, to secret paths and unexpected rewards. The game is built to be run in a Jupyter Notebook or directly via Python. It harnesses modules like `random`, `time`, and `colorama` to enhance user interaction with dynamic messaging and color-coded outputs.

---

## Features

- **Interactive Decision Making:** Your inputs determine the storyline and outcomes.
- **Dynamic Gameplay:** Encounters include battles, puzzles, and environmental challenges.
- **Colorful Output:** Using the `colorama` library, the game provides visual effects (green for victory, red for defeat, etc.).
- **Multiple Endings:** Experience different outcomes based on your choices.
- **Modular Design:** Organized functions (e.g., `cannibal_island`, `alligator_bay`, and `village`) style the game into self-contained episodes.

---

## Prerequisites & Installation
- ### Tech Stack
  
  - **Python:** Core language.
  - **Colorama:** For colored terminal output.
  - **Time & Random:** Built-in libraries to manage game flow.
  - **Jupyter Notebook:** Optional environment for running interactive sessions.

- ### Before running the game
  ensure you have:

  - **Python 3.x** installed on your system.
  - The following Python packages:
  - `colorama`

  You can install `colorama` via pip:

  ```bash
  pip install colorama
  ```


## Usage
## Input Syntax & Commands
The game expects interactive input at several stages. Below are some of the common commands and their roles during gameplay:

- **Difficulty Selection**:

  - Inputs: 1 (Easy), 2 (Medium), 3 (Hard) Example: When prompted "Choose your difficulty level (1: Easy, 2: Medium, 3: Hard):", type 1 and press Enter.

- **Direction Choices**:

  - Inputs: "east" or "west" Example: At the branching prompt, type east to explore the cave or west to explore the ocean route using the raft.

- **Game Decisions**:

  - Inputs: proceed, explore, or backtrack Example: When facing obstacles like a lava pit or secret passage, your decision is key. Type proceed to continue forward.

- **Riddle & Puzzle Answers**:

  - Input Example: For the riddle "I speak without a mouth and hear without ears…", type answers like sound, noise, or voice as your guess.

- **Game Replay**:

  - Inputs: yes to restart, no to exit Example: At the game over screen, choose yes to play again or no to exit the game.

## Running the Game
- From a Notebook: Run all cells in `Game_Project_V2.ipynb`. The interactive prompts will appear in your notebook’s output.

- From the Command Line: Launch the game directly in your terminal if you have refactored the code to run as a script (e.g., python `game_project_v2.py`).

## Code Structure
The project is organized into several key components:

- **Main Functions**:

  - `home()`: Initializes the game, sets health and points, and welcomes the player.

  - `cannibal_island()`: Handles the encounter on Cannibal Island.

  - `alligator_bay()`: Manages the sequence at Alligator Bay, including health checks and directional outcomes.

  - `village()`: Resolves interactions within the village, determining whether the player trades items or engages in combat.

- **Utility Methods**:

  - `fprint()`: A custom printing function (utilizing colorama) for formatted outputs.

  - `award_points()`: Increases the player’s score.

  - `game_over()`: Displays the final score and terminates the game.

Advanced error handling, console resets, and weather effects (e.g., the Heatwave reducing health) are all integrated to enrich the gameplay experience.

## Screenshots

- Main Menu / Welcome Screen: 



![Game-Main-Menu](https://github.com/user-attachments/assets/af7ce1c0-b0a5-4964-b6ff-48b67a56c953)


- Gameplay Section: Captures an interactive game session, such as a riddle challenge in the Mystery Room, in the example shown below, before proceeding to the Lava Pit room.



![Game-GamePlay-Example](https://github.com/user-attachments/assets/07e0fd94-24a5-4a7e-a10a-e2c5d19453c1)


- Game Over / Final Score: Include a screenshot of the game over scene with the final score displayed.



![Game-Game-Over](https://github.com/user-attachments/assets/ac400fb4-f536-47a9-b248-21c78d70bca0)




## Contributing
Contributions are welcome! If you'd like to enhance the game or fix issues, please follow these steps:

- Fork the repository.

- Create a new branch with a descriptive name (e.g., feature-enhanced-dialogue).

- Please make sure to commit your changes with clear messages.

- Push your branch and open a pull request detailing your changes.


## License
This project is released under ...

## Acknowledgments
- Special thanks to the Python community for continuous inspiration.

- Appreciation for the creative minds behind interactive text-based adventures.

*Embark on your adventure and see where your choices take you on The Mystery Island!*
