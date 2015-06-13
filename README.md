# Hide and Seak

This is the final project for CS-AD 101 Intro to CS with Prof. Michael Paik at NYU Abu Dhabi. It is developed by Koh Terai 17' and Maverick Alzate '16. This game is created using the [pygame module](http://www.pygame.org) which must be installed in order to run the program.

To run the game execute `python HideAndSeak.py`.

<h2>Game Objective</h2>
The game has a 10*10 map with a hundred squares. The player can move around the map with the `arrow` keys, drop a bomb with the `d` key, and pick up a bomb with the `p` key. The player will lose if the enemy players reach the player's home base or if the player's health bar reaches 0. The player wins if they are able to drop a bomb on top of the boss house.

The player must drop the color coded bombs on top of the same colored house to blow it up. When a bomb is dropped, the house will blow up revealing a new bomb. If a player collides with one of the enemies a battle sequence will begin.

<h2>Implementation</h2>
All of the graphics is implmented under the `GUI` class. Running the `game()` function will create a `square_map` array with 100 items, reach representing a square on the map.

Defeating the boss will reveal a special animation sequence featuring our beloved professor.