cse210-05

CYCLE

Overview

Cycle is a game where the players try to cut each other off using cycles that leave a trail behind them.

Rules

Cycle is played according to the following rules.

Players can move up, down, left and right...
Player one moves using the W, S, A and D keys.
Player two moves using the I, K, J and L keys.
Each player's trail grows as they move.
Players try to maneuver so the opponent collides with their trail.
If a player collides with their opponent's trail...
A "game over" message is displayed in the middle of the screen.
The cycles turn white.
Players keep moving and turning but don't run into each other.

The project files and folders are organized as follows:

root                    (project root folder)
+--  Cycle              (source code for game)
  +-- constance.py      (constant datas for game)
  +-- game              (specific game classes)
  +-- __main__.py       (entry point for program)
+-- README.md           (general info)
Required Technologies

Python 3.8.0
Raylib Python CFFI 3.7
Authors

Team and responsibilities:

Elizeu Silva: fer21029@byui.edu - classes Actor, Cast, Player1, Player2, Score
Alexander Karasik: kar21020@byui.edu -classes Action, Control_actors_action, Draw_actors_action, Handle_collisions_action  
Shawn Yang: yangshawn14@byui.edu - class Move_actors_action, Script, Keyboard_service
Brenner Mann: man19032@byui.edu - classes Director, Color and Point
Josifini Tamanalevu : josifini1234@gmail.com - class Video_service
