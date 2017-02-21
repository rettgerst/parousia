# Parousia: Rules

## Characters (and character sheets)
The _character sheet_ is a sheet that contains all of the relevant information about your character, as well as marked areas to place cards. It is technically optional but it helps a lot.

Character sheets will contain a number of hexagons in different places with numbers inside of them. The outline of a D20 forms a hexagon when viewed face-on, so the hexagons on the character sheets indicate that you should place a D20 there should you wish to track stats and pickups with D20s. You can count these using other means, like pencil and paper or computer/phone software, but regardless, all counters max out at 20, except for red hearts which max out at the current value of the _red heart container_ counter, and the _activated item charge_, which will be noted on its card. The number inside the hexagon is the number the counter should start at, aka the "base stat".

These are all of the counters:
 - Pickups:
	- Coins*
	- Hearts
	- Bombs
	- Keys
 - Character stats:
	- Heart containers
	- Damage
	- Speed
	- Tears/fire rate
 - Other
	- Activated item charge
	- Devil die

*During cooperative play, coins are shared among all players. Therefore if players wish to track their stats with D20s, you will need 9 D20s each, plus one for the shared coin counter.

## Decks

### Pickup deck

The pickup deck is made of a Solitaire deck including 2 jokers, and the major arcana from a tarot deck excluding _The Fool_, shuffled together.

Each suit in the solitaire deck corresponds to a specific pickup:
 - Hearts: Red hearts
 - Diamonds: Coins (aka cents or c)
 - Spades: Keys
 - Clubs: bombs

The number of the solitaire cards corresponds to a different function:

 - Ace: playable card which converts all pickups on the floor to the pickup correspondinng to its suit
 - Two: 2 of the corresponding pickup
 - 3-10: 1 of the corresponding pickup
 - Jack of diamonds: Nickel (5c)
 - Queen of Diamonds: Dime (10c)
 - King of Diamonds: Quarter (25c)
 - Face card of any other suit: two of the corresponding pickup

If the player cannot or does not wish to take the pickups produced by these cards they are put on the floor.

Each tarot card is a playable card which has a specific effect when played:

 - I (The Magician): ???
 - II (The High Priestess): Deals 10 damage to the enemy with the highest HP in the room.
 - III (The Empress): Triggers the effect of the Whore of Babylon (+2 damage for the rest of the combat phase)
 - IV (The Emperor): skip directly to the boss room and immediately start the combat phase
 - V (The Heirophant): drops 2 soul hearts on the floor
 - VI (The Lovers): drops 2 red hearts on the floor
 - VII (The Chariot): for 6 turns, the character cannot shoot, has +2 speed, deals contact damage to enemies, and is invulerable
 - VIII (Justice): drops one of each basic pickup (red heart, coin, key, bomb)
 - IX (The Hermit): Takes the player directly to the shop
 - X (Wheel of Fortune): card is moved to the floor and represents a slot machine which has a 10/20 chance to drop a random pickup from the floor
 - XI (Strength): +1 to all character stats until the end of the combat phase
 - XII (The Hanged Man): the player takes no contact damage this combat phase
 - XIII (Death): Deals 40 damage to every enemy in the current combat phase
 - XIV (Temperance): card is moved to the floor and represents a blood donation machine which drops D20/5 coins
 - XV (The Devil): +2 damage until the end of the combat phase
 - XVI (The Tower): spawns D20/2 bombs on the floor which can damage the player
 - XVII (The Stars): travel directly to the treasure room
 - XVIII (The Moon): 2/D20 chance to spawn a random item, else spawns a random pickup
 - XIX (The Sun): fully heal the player, and the shop, treasure room, arcade, and boss room are now revealed and can be used at will (players can still draw rooms if they wish)
 - XX (Judgement): card is moved to the floor and represents a beggar, which has a 1/D20 chance to spawn an item, else a 3/D20 chance to spawn a pickup, else does nothing
 - XXI (The World): the shop, treasure room, arcade, and boss room are now revealed and can be used at will (players can still draw rooms if they wish)

## Play areas

 - The floor: any items or pickups not yet consumed, or interactive objects like beggars. All cards are removed from the floor and reshuffled back into the pickup deck when the players proceed to the next floor.
 - Hand: every player has a "hand" which can hold a maximum of 1 playable card (this maximum can be increased by items)
 - Combat area: all enemies and enemy tokens are put in the combat area during the combat phase, and placed on the _bottom_ of their respective deck at the end of the phase
 - Items: all collected items, no maximum
 - Activated item: each player can hold one "activated item" (unless that activated item has been consumed by _Void_, then form a deck with Void on top)

## Rooms

Whenever players finish a combat phase they can draw a new room from the room deck. Some rooms also come with a "chaser" (this term is borrowed from _Red Dragon Inn_), where players draw another room and combine their enemies into one combat phase. If the chaser room is a special room like the treasure room, boss room, shop or arcade, it is discovered but cannot be entered until the end of the combat phase, and they have to draw another room until they draw a non-special room. Chasers can also form chains with other rooms requiring chasers.

Some room cards will also show pickup icons next to spikes, rocks or locks, meaning they have an extra pickup in that room but the player must spend a hit of contact damage, bomb or key to collect them.

### Special rooms

Special rooms include the boss room, the shop, the treasure room and the arcade. These rooms, when drawn, are "discovered" which mean they can be traveled to and used when outside of the combat phase, but do not need to be entered immediately.

#### Shop

Draw two items and three pickups, put them on the floor, and tap them to indicate they haven't been bought yet. Pickups can be bought for 5c and items for 15c. If two of the pickups are hearts, one is a soul heart and the other a red heart.

#### Treasure room

The treasure room contains one item from the top of the item deck. On any floor besides the first floor it requires 1 key to enter.

#### Arcade

the arcade contains a slot machine, a beggar and a blood donation machine.

#### Boss room

Upon entering the boss room, a boss is drawn from the boss deck and the combat phase is immediately started with that boss.

Upon completing the boss fight, note the value curently tracked by the Devil Die, then roll it. If the number you rolled meets or exceeds the noted value, the devil room opens and you can make a Devil Deal.

#### Devil room

The devil room is a _special_ special room that does not exist in the room deck, but is entered with a _Joker_ card or has a chance of spawning after the boss fight.

Upon entering, draw two items from the devil item deck. These can be bought for the price in red heart _containers_ listed on the card. Three soul or black hearts are equivalent one red heart container.

## Combat

Characters take their turns in order of decreasing speed. Characters with _charge_ always go _after_ characters without _charge_. (_Charge_ means that characters have to "charge" their attack before firing).

Players, during their turn, roll D20s to determine if they kill enemies. Their tears/fire rate stat determines the number of dice they can roll. They start by selecting a target, then roll a D20. If the number rolled + their _damage_ stat meets or exceeds the enemy's _resilience_ stat the enemy is hit. If the enemy has a next form it enters that form, else it dies. This process repeats until the player is out of rolls. Then the next character starts their turn.

On enemy turns, enemies automatically target the player character with the lowest speed (_not_ the one last in the turn order). If they have an _accuracy_ stat, they do a hit of damage to the targeted player if their accuracy + a D20 exceeds the target's speed. If their speed exceeds the target's speed, they can also do a hit of contact damage to the target, but not if they've already done damage to that target that turn.

Bosses are slightly different from non-boss enemies in that they have HP, and have an _evasiveness_ stat instead of _resilience_ which is typically lower but otherwise functions the same. Players deal damage equal to their _damage_ stat to bosses when their damage + D20 meets or exceeds the boss's _evasiveness_, and can hit bosses multiple times in a turn.

At the end of every combat phase, drop a random pickup and add 1 to every player's activated item charge.

If a player takes red heart damage during a non-boss fight, increment their devil die by 1 (but only once per fight). If a player takes red heart damage during a boss fight, increment their devil die by 2 (but only once per fight). When a player advances to the next floor, halve their devil die if they didn't make a devil deal on that floor.

# Glossary

**Random:** From the top of the corresponding deck

**Chance:** if a rule shows (x/D20) chance that means roll a D20 and the effect is applied if the die roll meets or is less than x. If this is followed by "else" this works like a cascading series of if/else statements applied to the same die roll.

**Fight:** shorthand for "combat phase"
