# rpg-game

# Text-Based Adventure Game

This JavaScript code is for a text-based adventure game. Here's a brief overview of the game's functionality:

## Variables
The game uses several variables to track the player's experience points (`xp`), health, gold, current weapon, and inventory. There are also variables for the fighting state and monster health.

## HTML Elements
The game uses the `document.querySelector()` function to access various HTML elements in the game interface, such as buttons and text fields.

## Weapons and Monsters
The game includes arrays of objects representing different weapons and monsters that the player can use or fight against.

## Locations
The game has several locations that the player can visit. Each location has its own set of actions that the player can perform.

## Functions
The game uses several functions to control the game flow and player actions. Here are some key functions:

- `goTown()`, `goStore()`, `goCave()`: These functions take the player to different locations.
- `buyHealth()`, `buyWeapon()`, `sellWeapon()`: These functions allow the player to buy health, buy weapons, or sell weapons.
- `fightSlime()`, `fightBeast()`, `fightDragon()`: These functions initiate fights with different monsters.
- `attack()`, `dodge()`: These functions control the player's actions during a fight.
- `defeatMonster()`: This function is called when the player defeats a monster. It rewards the player with gold and experience points.
- `lose()`, `winGame()`: These functions are called when the player loses or wins the game.
- `restart()`: This function resets the game to its initial state.
- `easterEgg()`, `pickTwo()`, `pickEight()`, `pick()`: These functions control a hidden easter egg game where the player can win extra gold or lose health.

## Gameplay
The player navigates through different locations, fights monsters, buys and sells weapons, and tries to defeat a dragon. If the player's health reaches zero, they lose the game. If they defeat the dragon, they win the game. The player can also play a hidden easter egg game to win extra gold or lose health. The game can be restarted at any time. 

Please refer to the code comments for more detailed information about each function and variable. Enjoy the game!