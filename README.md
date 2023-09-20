# Dodge_Game
This document provides documentation for a Python implementation of a simple Dodge Game. The game is built using the Pygame library.




Table of Contents:
1. Game Setup
2. Game Objects
3. Game Loop
4. Restart Functionality
5. Collision Handling
6. Game Over Handling
7. Scoring
8. Conclusion

1. Game Setup:
   - The game initializes Pygame and sets up the game window with a specified width and height.
   - Game assets, including player and enemy images, are loaded.
   - The player and enemy objects are created as sprites.

2. Game Objects:
   - Player class: Represents the player character.
     - Initializes the player's image, position, and movement speed.
     - Defines the update method for player movement.

   - Enemy class: Represents enemy objects that the player must avoid.
     - Initializes enemy images, positions, and random speeds.
     - Defines the update method for enemy movement.

3. Game Loop:
   - The game runs in a loop until the player quits.
   - Event handling allows the player to restart the game by pressing the 'R' key.

4. Restart Functionality:
   - The restart_game function is defined to reset the game state.
   - It clears all sprites, including enemies and the player.
   - New player and enemy objects are created.
   - The game_over variable is set to False to resume gameplay.

5. Collision Handling:
   - The Pygame spritecollide method is used to detect collisions between the player and enemies.
   - If a collision occurs, the game_over variable is set to True.

6. Game Over Handling:
   - If game_over is True, the game enters a game over state.
   - The game screen is filled with a white background.
   - "Game Over" and "Press 'R' to restart" messages are displayed at the center of the screen.

7. Scoring:
   - The player earns points by avoiding enemies.
   - The score is displayed on the screen.

8. Conclusion:
   - This Python implementation of the Dodge Game provides a simple and interactive gaming experience using the Pygame library.
   - Players control a character and attempt to avoid oncoming enemies to earn points.
   - The game includes functionality to restart the game after a game over condition.

Note: This documentation provides an overview of the code structure and functionality. Detailed code comments can be found within the Python script for a more comprehensive understanding of the implementation.


