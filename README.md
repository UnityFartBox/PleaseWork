README (copy this into your repo)
# <Isotope>

GAME 360 - Dylan O'Brien

 

## How to play

WASD - Moves the Player
(Arrow Keys may also work)

 Collect the coins to get your score to 100 to win
 You have 3 lives

## Singleton

Class: GameManager.cs

What it holds: player score / amount of lives / game state / enemy collision and damage

Why it's a singleton: Holds all the parameters needed to allow for the game run and is depended on by multiple different attributes for the game.

 

## Observer

Event: <EventName> in <ClassName.cs>

Listener 1: ScoreManager.cs - Listens to how many coins / collectibles are collected by the player allowing for the score to increase periodically

Listener 2: EnemyAction.cs - Observes where the player moves on the screen and slowly follows the player, the enemy also flashes a different color when the Player collects the coins

## Help I used

I used ChatGPT to help me create and revise a few scripts to add the finishing touches towards the game, such as the Enemy Damage, Game Over screen, and the replay button. Doing so required me to make a few changes to scripts that I had already implemented before utilizing this tool however.
