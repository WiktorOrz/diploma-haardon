# Haardon
**Haardon** is a game combining RTS and FPS gameplay, created as a group diploma project for my Bachelor's Degree.
## Download the full Unity project (ZIP)
[Download from Google Drive](https://drive.google.com/file/d/1hi0YNQ2IGXp4Lpua_PjiJznSIGvt9Z_j/view?usp=sharing)
## Watch Trailer-Showcase
[Video](https://youtu.be/Y5CoLYRVqSE)
# Full project details below.
## Project Description
**Haardon** is a Unity game that merges the gameplay of Real-Time Strategy (RTS) and First-Person Shooter (FPS) games.
It was created as a group project for our diploma at Polish-Japanese Academy of Information Technology. Our group wanted to create a game we would love to see, blending the tactical gameplay of RTS games and the action packed and immersive combat of FPS games.

The main loop of the game is divided into two main phases:
- Building Phase, during which the player can construct buildings, generate resources as well as train units and set up their positions.
- Fighting Phase, during which the player can switch between FPS and RTS modes. In RTS mode, the player can order their units to attack enemies, while in FPS mode, they control the main character.

This project is not a full game, but it serves as a good prototype of how a combination of those two game types can look like.

## Technologies Used
For this project we have used the Unity game engine, with programming done in C#. We have also used public libraries.

## Features
### RTS/Building Phase:
- Resource System: Metal and Energy used for construction and unit production.
- Building System: Includes building creation and control. Buildings included are the main base, barracks, resource collectors, and energy generators.
- Unit System: Multi-Selection, movement, A* Pathfinding.
- Health System: Units and buildings have hit points.
### FPS-RTS/Combat Phase:
- Wave System: Enemies spawn in increasingly difficult waves.
- Enemy and ally troops pathfinding and fighting systems.
- Mode Switching: On a press of a button, switch between RTS and FPS modes.
- Hero Abilities: Teleport, healing aura, slow time, multishot, airstrike.
- Weapons: Rifle and Grenade Launcher with reload and ammo mechanics.
### Additional Systems:
- Music Manager: Dynamic music based on game phase (menu, building, combat, win and lose).
- Grid System: Used for building placement and pathfinding.
- Animations: Full animation sets for characters, buildings and enemies.
- Maps: Different map sizes with procedural terrain generation.
- Save System: Saving and loading the game from the pause menu and main menu.
- Raycasting System: For unit and building selection.
## How to Run
The .ZIP file linked above contains the full Unity project, not the completed build. To run:
- Download the .ZIP and unpack it.
- Open it in Unity (tested on Unity 2021.3.24f1).
- Open the *Final* scene and run.
## What I learned
This project has challenged me as a programmer and as a team member. I have learned how larger scale projects work in game development and it has allowed me to work on a game on a scale I have never worked on before. It has allowed me to progress my abilities in planning and executing the plans for the game, especially in the parts I have worked on primarily, which were special abilities, enemy scripts, UI, buildings and music. It has also taught me how to work on a larger project with other people.
## Possible Improvements
Things I would like to be improved are:
- Graphical Design: due to the fact that our team was comprised of developers only, we were forced to use free assets.
- Better AI: The AI of enemies in this game was very simple, focusing on destroying the player or a building if the player wasn't detected nearby. Tactical movements and decisions could be a massive improvement.

### This project is shared for demonstration and portfolio purposes only. Ownership and reuse may be subject to university IP policies.
