U.S. States Game 

Project Overview
This project is an interactive geography game built using Python Turtle graphics and Pandas. The game displays a blank map of the United States, and the player must guess the names of all 50 states. Correct guesses are written onto the map at their respective coordinates.

Files Required

1. main.py – The Python script containing the game logic.
2. 50_states.csv – Dataset containing state names with their x and y coordinates.
3. blank_states_img.gif – Blank U.S. map image used as the game background.
4. states_to_learn.csv – Auto-generated file listing states the player missed (created when the player exits early).

Requirements
Python 3.x must be installed.

Required libraries:

* turtle (built-in with Python)
* pandas

Install pandas if not already installed:
pip install pandas

How the Game Works

1. The program loads a blank U.S. map using Turtle graphics.
2. It reads state data (names and coordinates) from the CSV file.
3. The player is repeatedly prompted to enter a state name.
4. If the guess is correct:

   * The state name is displayed at the correct map location.
   * The score increases.
5. The loop continues until:

   * All 50 states are guessed, or
   * The player types “Exit”.

Exit Feature
If the player types “Exit”:

* The program compares guessed states with the full list.
* Missing states are saved into states_to_learn.csv.
* This file can be used later for revision or practice.

Game Controls
Input is handled through a text popup dialog box.
Type state names and press Enter.
Type “Exit” to quit early.

Learning Objective
This project helps practice:

* Python loops and conditionals
* Lists and data filtering
* File handling with Pandas
* Turtle graphics positioning
* Basic game logic design

Possible Improvements

* Add a timer
* Track high scores
* Provide hints
* Color states after guessing
* Add sound effects

How to Run

1. Place all required files in the same folder.
2. Open terminal or command prompt in that folder.
3. Run:
   python main.py

The game window will open and prompts will appear for guesses.

