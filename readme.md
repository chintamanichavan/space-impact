# Space Impact Game

This is a simple Space Impact game implemented in Python using the Pygame library. The game allows you to control a player spaceship, shoot bullets, and avoid enemy spaceships.

## Requirements

- Python 3.x
- Pygame library

## How to Run

1. Make sure you have Python installed on your system.
2. Install the Pygame library by running the following command:
   ```
   pip install pygame
   ```
3. Save the code provided in a file named `space_impact.py`.
4. Open a terminal or command prompt and navigate to the directory where the `space_impact.py` file is saved.
5. Run the following command to start the game:
   ```
   python space_impact.py
   ```

## Instructions

- Control your spaceship using the **Left** and **Right** arrow keys.
- Press the **Space** bar to shoot bullets.
- Avoid colliding with enemy spaceships.
- Shoot down enemy spaceships to earn points.

## Controls

- **Left** Arrow Key: Move spaceship to the left
- **Right** Arrow Key: Move spaceship to the right
- **Space** Bar: Shoot bullets

## How it Works

- The game uses the Pygame library to create the game window and handle user input.
- The player's spaceship and enemy spaceships are represented as sprites.
- The player's spaceship can be moved left or right using the arrow keys.
- The player can shoot bullets by pressing the space bar.
- The enemy spaceships move down the screen at different speeds and reappear at the top when they reach the bottom.
- When bullets collide with enemy spaceships, both the bullet and the enemy spaceship are destroyed, and new enemy spaceships are created.
- The game detects collisions between the player's spaceship and enemy spaceships. If a collision occurs, the game ends.
- The game continuously updates the game window to display the player's spaceship, enemy spaceships, and bullets.
- The game loop handles user events, updates the positions of sprites, checks for collisions, and redraws the game window.

Feel free to modify and enhance the code as per your requirements. Enjoy playing Space Impact!
