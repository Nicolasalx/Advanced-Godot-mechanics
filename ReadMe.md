### Advanced-Godot-Mechanics
[Godot Documentation](https://docs.godotengine.org/fr/4.x/getting_started/introduction/introduction_to_godot.html)

#### ex00 - Install Godot
Download and install Godot on your machine. Ensure successful installation by launching Godot.

#### ex01 - Create a New Project and Scene
Launch Godot and create a new project. Add a new 2D scene by clicking on "Create New Scene".

#### ex02 - Add and Configure a Map Sprite
Find a map sprite and add it to your 2D scene. Configure the map sprite with collision shapes so that the player can't move out of bounds.

#### ex03 - Add a Player Sprite to the Map
Find a character sprite and place it on the map. Add a KinematicBody2D node to the character and configure it for movement. Ensure the character has collision shapes. Implement a health system for the player.

#### ex04 - Create Your First Script!
Create a script to enable your character to move when the "zqsd" keys are pressed. Implement smooth movement with acceleration and deceleration. Ensure the script handles collision detection with the environment and other objects.

#### ex05 - Add Different Animations
Add 4 character sprites with different animations for moving right, left, up, and down. Implement a state machine in your script to manage these animations and ensure they transition smoothly based on movement direction and state. Add animations for idle states and different actions like jumping or attacking.

#### ex06 - Collect Gems
Place gems on the map and ensure each gem has a collision shape and is part of a "collectibles" group. Modify your script to detect collisions with gems and add them to an inventory. Implement a UI element to display the inventory on the screen. Add a scoring system that updates based on the number of gems collected and displays the score in the UI.

#### ex07 - Make an End Animation
When your character has collected 3 gems, add an ending animation with images to indicate that the game is over. Ensure this end sequence includes a transition back to the main menu or a restart option. Add a cinematic sequence using Godot's AnimationPlayer to make the ending more engaging.

#### ex08 - Implement Enemy AI
Add enemy sprites to the map with basic AI. These enemies should patrol predefined paths and chase the player when in range. Ensure the player can take damage and has a health system in place. Implement different types of enemies with varying behaviors and difficulty levels.

#### ex09 - Power-ups and Abilities
Add power-ups to the map that grant the player temporary abilities, such as increased speed, invincibility, or new attacks. Implement a timer system for these power-ups and ensure they are displayed in the UI. Add cooldowns for abilities to make the gameplay more challenging.

#### ex10 - Advanced Level Design
Create a multi-level game where the player transitions between levels. Implement checkpoints and save the player's progress. Design levels with increasing difficulty and include environmental hazards such as spikes, moving platforms, and traps. Add puzzles that the player needs to solve to progress.

#### ex11 - Boss Fight
Design a boss fight for the final level. The boss should have multiple attack patterns and phases. Implement health bars for both the boss and the player, and create a dramatic ending sequence upon defeating the boss. Add mechanics that require the player to use skills learned throughout the game to defeat the boss.

#### ex12 - Dynamic Sound and Music
Add background music and sound effects to your game. Ensure that the music changes dynamically based on the player's progress and actions. Implement spatial audio for a more immersive experience.

#### ex13 - Implement Save and Load Functionality
Create a system to save the player's progress, including their position, health, inventory, and current level. Implement load functionality to restore the game state from a saved file. Ensure that the game can handle different save slots.

#### ex14 - Networked Multiplayer Support
Add networked multiplayer support, where players can join a game session and collaborate or compete to collect gems and defeat enemies. Implement synchronization of player movements, actions, and game state across the network. Ensure the game is stable and handles latency and disconnections gracefully.

#### Bonus
Experiment with advanced visual effects like shaders and post-processing to enhance the graphical quality of your game. Add support for custom mods where players can create and share their own content using your game's mechanics.
