# Space-Invaders-Pygame
A pygame Implementation of the popular Classic Atari and NES Arcade games

This is a part of a series of Classic Arcade Games implemented in Pygames. list of games in this collection:

1. Space Invaders (my version)
2. more coming soon . . .

# Space Invaders
The classic Space Invaders was the first blockbuster arcade video game, responsible for starting the golden age of video arcade games. It also sets the template for the shoot 'em up genre, and influences nearly every shooter game released since then.

The classic Space Invaders 1978 was created by Tomohiro Nishikado and was released by Taito Corporation in the year 1978.
# Concept

In my Implementation of the game, the concept remains the same, i.e the player spaceship shoots the aliens or monsters and in doing so gain points followed by level ups and increase in game speed and difficulty.

What differs from the classic implementation and the features are are listed below:

1. In each level, the number of enemies equals the level number, unlike the classic version in which there are 55 enemies each level.
2. After a certain number of kills, the difficulty goes up, resulting in a speed increase of the aliens.
3. The enemy keeps on respawning and will never die completely.
4. The enemy may shoot a laser beam depending on random chance or probability.5.
5. The random chance or probability of the enemy shooting you goes up as level increases.
6. The score is incremented on a successful kill and the value is based on the level number and difficulty number.

# Features
The features of the game is as follows:

1. The player can be moved left or right using the Left Arrow and Right Arrow keys.
2. The game can be paused (v1.1.2 onwards) with Enter key or Esc key.
3. The player levels up with increase in number of enemies and a level up sound (v1.1.1 onwards)
4. The game has a background music (the classic Space Invaders music) which changes and becomes more intense with increase in difficulty.
5. The game pause has the classic sound effect
6. Each game object and every Interactions has sound effects.
7. The game has key logging feature and every input is logged into the console
8. The game also has FPS Tracking and Each Frame Render time in miliseconds and displays it in the game.

# Gameplay
Here is a short gameplay of the game 

https://user-images.githubusercontent.com/71597104/144576208-a9535259-1454-43e6-8275-9753245f8e4b.mp4

# Installation
On windows:

1. ensure that you have python and pip on your machine. If not, install it from here.
2. clone the repo to a local directory or download it as zip and un-zip it.
3. open windows command prompt (cmd) and enter the following commands:
4. create a virtual environment py -m pip install --user virtualenv
5. py -m venv env
6. activate the virtual environment .\env\Scripts\activate
7. install the game dependencies from the requirements.txt file using the command pip install -r requirements.txt
8. navigate to main.py and launch the game using the command cd Space Invaders && python main.py

you can skip creating a virtual environment if you wish and ignore steps 4-6 but it is not recommended.



