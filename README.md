# Drone Attack

Developed with Unreal Engine 5.2

# Game Mechanics

The game has various game states, health and ammo pick ups and simple user interface. Enemies have thier own patrol paths and alert when the player is close.

# Health and Stamia

The game has health bar at the top of the screen to show when the player has been damaged. The player can heal by walking by health pickups. The stamia bar is at the bottom.

# Movement and Animations

The movement system was created using unreal engine blueprints and state machine to transition between different animations.
The sprinting animation is enabled by holding the shift button and when the button is released the player is in walking state.
The jumping movement is enabled by pressing the space bar.

# Game States
## Warmup State:
- The countdown timer will appear on the screen. Counting down to 3.
- The player's movement is disabled during this period.
## In Progress State:
- Show the time remaining to eliminate all the drones in the encounter.
- The number of drones left.
- Drones are patrolling.
## Out of Time State:
- When the player runs out of time and there are still drones on the map, the player loses.
- Lost the Game!
## Player Died:
- If the player died, the game is lost.
## Player Won:
- If the player successfully eliminates all the drones before the time runs out.
# Enemy AI
The drones all have thier individual patrol points. They have different patrolling paths. Can be aggro when player gets too close or starts shooting.

# DevLog:
[DevLog Doc](https://docs.google.com/document/d/13kHtDW3JpqM30btkvsuDmZV94Z_lFjCVKeO1Twa4A64/edit?usp=sharing)
