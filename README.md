# Checkers

AI agent that solves Checkers games.
(created for Aritificial Intelligence course taken at UCI)

Submitted by: **Alexis Vu & Karla Abad-Torrez**

## Required Applications
* Command-line

## Specifications (adapted from <a href=https://gitlab.ics.uci.edu/ai-projects/Checkers_Student/wikis/checker-game-mechanics name>course site</a>)
* Environment 
  - Executes within shell
  
* Sensors
  - Agent only knows of opponent's most recent move (represented by Move object)

* Actuators
  - Agent returns a move (represented by Move object) to indicate to shell where it will be relocating
  
## Running the AI
Note: First, compile using **make** from the source root.

* **Manual Mode**
  - ,/main {#col} {#row} {p} m {start_player (0 or 1)}

* **Self-play Mode**
  - ./main {#col} {#row} {p} s {start_player (0 or 1)



