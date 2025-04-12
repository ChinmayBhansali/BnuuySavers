# [Bnuuy's Ship](https://bnuuysavers.itch.io/bnuuys-ship)
Bnuuy Savers (Team) - Brian Moniaga, Chinmay Bhansali, Clare Pan, Dayshaun Lee, Lily Zhang

# M1

### Smooth Interpolation Implementation

We did an interpolation for the player's healthbar changing the color from green to red as the value (Player's HP) decreases using linear interpolation. 

We did a linear interpolation by changing the player's texture. By waiting after a set time, it will interpolate into the next keyframe.

### External Integration

We used [Tileson](https://github.com/SSBMTonberry/tileson) to parse maps and create entities/components from the parsed maps.

### Precise Collisions

We implemented precise collisions to allow for convex and non-convex shapes.

# M2

### Advanced Decision-making

We implemented A* searching algorithm to the enemies for the creative component. The enemies will find the shortest path from their current location to the ship's location, while avoiding island collisions.

# M3
## Features Added
- Better Tutorial Level
- Randomized Reward System (Gacha System)
- More Levels
- Ship Expansion
- Laser Weapon
- Bubble Buff
- Build Mode
- Enemies Respawning
- Radar System
- Different Enemy Types
- Healing Module
- Obstacles (Whirlpool & Tornado)

## Creative Components

### Audio Feedback
Different game states will play audio feedback accordingly. Such as when an enemy collided with the ship or when a projectile is shot.

### Reloadability
Completing a level will save the game to a save file. The player may choose to continue the game from their last save (load the game from the save file).

### Basic Integrated Assets
We have a wide variety of game sprites that have the same art styles (pixel style).
### Camera Controls.
Camera view throughout the gameplay. Things other than the player, UI, ship, and modules stay in the background as the ship moves.

# M4

## Creative Components

### Particle System
Used instanced rendering to create a particle system.
