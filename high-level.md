# Parousia High-Level Design Document

## High Concept
This is a tabletop game inspired by the video game series "The Binding of Isaac".
## Features
 - Single-player or cooperative gameplay
 - Roguelike
 - Theoretically infinite gameplay
 - Unique game every time the cards are shuffled
 - Fast as possible: "randomness" is seeded by card shuffle wherever possible, with minimal dice rolling, and combat is greatly simplified for fast, frantic gameplay
 - Much of the materials can be acquired from hobby shops or re-used from other games
 - No human opponent or "DM" required, all level design and enemy behavior is generated on-the-fly by random card draw or die roll, with clearly defined rules
 - Collectible "items" impact game experience heavily, and allow player(s) to radically alter their game experience, and also introduce an element of strategy

## Player motivation
The game can be played in a few different ways. It can be played cooperatively to see who lives the longest, or solo with a pre-set goal, or simply played infinitely to see how far the player(s) can get.

## Genre
Roguelike, with macabre, occult, and Judaeo-Christian themes

## Unique selling points
Infinite replayability, high degree of strategy

## Target hardware
Card and board

## Design goals
 - Fast-paced frantic gameplay: rules are simple, and use card draw from pre-shuffled decks wherever possible (versus dice roll which tends to be slower)
 - Standard roguelike experience: game can be played theoretically infinitely and each "run" is unique
 - Highly diverse strategy introduced by character selection and item collection

## Characters
 - Enemies: too many to list here, but mostly the same and details don't matter: enemies the player characters fight while searching for the trapdoor to the next floor
 - Bosses: Last enemies the players fight before the next floor is unlocked, typically a longer and harder fight than non-boss enemies
	- Monstro: easy to hit and dodge, larger health pool
	- Haunt: somewhat more difficult to hit or dodge, medium health pool
	- Little Horn: small health pool, very hard to hit
	- Rag Man: small health pool, easy to dodge, but very obnoxious as he spawns spiders
	- Horsemen (Famine, Pestilence, War, Death): small health pool, hard to hit but easy to dodge, multiple phases
 - Player Characters:
	- Isaac: main character of the game, well-rounded, starts with the D6 which can re-roll items
	- Azazel: "glass cannon" who starts with no heart containers but a very powerful charged attack, can be very effective in the hands of a skilled character
	- Eve: starts with low health but has a passive ability ("Whore of Babylon") which makes her very powerful at low health
	- Samson: similar to Isaac, but his damage increases as he loses health
	- Apollyon: Starts with low health, but starts with a very powerful item ("Void") which can improve his stats or merge with other items
	- The Lost: has no health and will die from one hit, but can take devil deals for free making him very powerful if he survives long enough
