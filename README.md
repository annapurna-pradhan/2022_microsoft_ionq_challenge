# PAQ-MAN - PAC-MAN with a quantum flavor

PacMan has been designed originally as an antidote to the games with violent themes. This game is very simple yet alluring to be used for educational purposes. Pacman eats dots in a maze to score points. It avoids the ghosts to be alive in the game. In return it increase the cumulative score.

We have utilized this simple game to understand the complex concepts of Quantum Mechanics.

This is the repository for the IQuHACK 2022 project.

Setup:
Draw the maze : This function sets the background of the screen for starting the game
Draw PacMan : We need to set a starting position and direction for PacMan.
Move PacMan
Increase the score : When Pac-Man moves over a dot, the score increases by one, and the dot is removed.
Add the ghosts : First, we need to add the starting positions of our ghosts.

## Dependencies

* Pygame
* Numpy
* Qiskit Aer
* Azure.quantum

## How to run

Just run main.py after installing dependencies! Move Pacman using the arrow keys.

## Game rules

* The objective is to score as many points as possible, while avoiding dying
* Pacman has an associated quantum state, and the ghosts perform measurements in X, Y or Z basis. If the measurement result is a 0, Pacman dies. If it's a one, Pacman starts in the post-measurement state. The measurement results and post measurement states are obtained by running the relevant code on a real IonQ quantum computer, accessed via Azure!
* There are gates strewn throughout the maze. If Pacman meets an X, Y or Z gate, the gate acts on the Pacman's state, and Pacman then is in the state obtained after the gate acts. 
* The gates and ghosts disappear after interacting with Pacman.
* The score is increased by CNOT and H gates, which allows Pacman to generate maximally entangled 2-qubit states.

# Screenshots 

![Main gameplay window](/screenshots/gameplay_1.png)

![Score increment after Pacman swallows an H gate](/screenshots/gameplay_2.png)

![Measurement being run on an IonQ quantum computer](/screenshots/gameplay_3.png)

![Post death :D](/screenshots/gameplay_4.png)

# Welcome to IonQ + Microsoft Joint Challenge @ MIT iQuHACK 2022!

PacMan has been designed originally as an antidote to the games with violent themes. This game is very simple yet alluring to be used for educational purposes. Pacman eats dots in a maze to score points. It avoids the ghosts to be alive in the game. In return it increase the cumulative score.

We have utilized this simple game to understand the complex concepts of Quantum Mechanics.

# Steps: PAQman

1. Setup:
2. Draw the maze : This function sets the background of the screen for starting the game.
3. Draw PAQman : We need to set a starting position and direction for PacMan.
4. Move PAQman
5. Increase the score : When PAQman moves over a dot, the score increases by one, and the dot is removed.
6. Add the ghosts : First, we need to add the starting positions of our ghosts.





