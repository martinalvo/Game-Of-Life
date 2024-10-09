
# About The Project

This project consisted of programing a customizable simulation of the Conway's Game of Life cellular automata
This automata consists of cells in a grid where each cell can be on or off. The value of each cell is determined by
the amount of nearby cells.

Rules of the simulation:
- Cells with two less than 2 neighbours will die, (turn off next generation)
- Cells with 2 to 3 neighbours will stay alive if alive (turn on next generation)
- Cells with exactly 3 neighbours will become alive if dead (turn on next generation)
- Cells with more than 3 neighbours will die (turn off next generation)

# Required Libraries

To use this simulation you will be required to have the Python Pygame module installed on your computer.

# Using the Simulation:

To initialize the simulation you must first run the program

This simulation has varius features:

Initializing the simulation parameters
* Set the window size you would like to simulate for. Each number is a a cell in length (Ex. 10x10 is 10 cells by 10 cells) 
* Set the Speed of the simulation: higher values make it slower
* Set the color of the simulation:
  * "normal" = white
  * "random" = random color
  * "custom" prompts to enter RGB values

Controls
* Use mouse left click to place live cells onto the grid
* left click on live cells to remove them
* SPACE runs the simulation
* UP_ARROW increases the speed
* DOWN_ARROW decreases the speed
* C randomly changes the color every generation
  * Toggle on/off
* W sets the color to white

Demo:

![](https://github.com/martinalvo/Hackathon/blob/main/HackAThon/Snake2.png)
<p align="right">(<a href="#readme-top">back to top</a>)</p>
