# Riot Dice
**Riot Dice** is an open source engine for chaotic dexterity-based tabletop miniatures games.

## What is Riot Dice?
Originally written as the core system of [SPACE GITS](https://planetsmashergames.com/space-gits), **Riot Dice** is an open source rules engine for chaotic dexterity-based miniatures games. It uses a number of dexterity-based mechanics, many building on the core idea that the location of rolled dice (relative to the models) should matter.

**Riot Dice** is copyright 2025 [Mike Hutchinson](https://planetsmashergames.com/) and licensed under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1).

## The License

If you are interested in making your own dexterity-based miniatures game, I welcome you to use the **Riot Dice** engine, which is offered under a Creative Commons license. Specifically: I offer the text of my **Riot Dice System Reference Document** ("SRD") under a [Creative Commons CC by 4.0 licence](https://creativecommons.org/licenses/by/4.0/). This allows you to remix, adapt, distribute and build upon in any medium or format, so long as you give attribution to me as the creator. The licence allows for commercial use.

If you do use the **Riot Dice** engine (or parts of it) in your game, ask that you credit me (Mike Hutchinson) and include the URL [https://planetsmashergames.com/riot-dice](https://planetsmashergames.com/riot-dice) in such accreditation. For example:

> [!TIP]
> _GAME_NAME is powered by Riot Dice, an open-source rules engine by Mike Hutchinson (https://planetsmashergames.com/riot-dice)._

I really hope you use this system, and make something cool and fun with it. If you use **Riot Dice** for anything, [let me know](https://planetsmashergames.com/discord/).


# Riot Dice by Mike Hutchinson

This is the Riot Dice System Reference Document. It describes the **Riot Dice** game engine. 

> [!TIP]
> _When you see a note formatted like this, this is an option that you can choose to use or ignore._

> [!WARNING]
> _Only the text contained in this **Riot Dice** System Reference Document is covered by the CC license; the text of the rulebook of [SPACE GITS](https://planetsmashergames.com/space-gits) is not._

> [!IMPORTANT]
> _This SRD is written in a dry and technical manner. It also makes sure to only mention each rule once, and specifically in the spot that it most needs to be. For example, you'll find the Damage rule in the section describing "The Tower". This is an attempt to make each section of the rules modular, to increase the hackability._

## The Basics

### Models
Models are 28mm miniatures, and should be mounted on bases between 20mm and 40mm.

> [!TIP]
> _Details such as model scale, legal base sizes and so on are entirely up to you. I just provide some defaults._

Models are defined by a set of Stats:
* **Cost**: The cost, in points, to add this model to your gang. All models cost 5 points.
* **Move Dice**: The dice you roll for this model when they make a Scoot Action. All have a Move of 3D6.
* **Toughness**: This is the number an opponent has to roll to successfully do Big Damage to this model. All models have a Toughness of 3.

> [!TIP]
> _You might want to add other stats, and create different classes of model that have different stats than the defaults given above._

### Players
Players are referred to as Bosses. A model's boss is the player that is controlling them.

### Measuring
When measuring and checking lines between dice and models, you can measure from anywhere on the models' bases to anywhere on the dice. If it grazes either, it is in. If you are using a vehicle without a base, measure from the hull. You can premeasure during your activation.

## The Tower
Each model has a personal dice tower of dice. 

When a model adds a dice to its tower, its boss adds a six-sided dice to this tower, placing it on top of the other dice in their tower to form a single stack of dice. 

The tower has to touch the model at all times. I.e. When you move a model, you have to move their tower with them.

> [!TIP]
> _For games that don't want or need a damage and/or "down but not out" mechanic, you could remove this whole "The Tower" section and not have dice towers. They aren't essential to the Riot Dice system. For example, I wrote a non-combat sports game that uses most the Riot Dice rules, but didn't need the tower. If you still want a damage system, you could use a simple HP stat for each model._

### Falling Dice
If any of the dice fall off a git’s tower at any point, for any reason, that tower has fallen, and the dice from the tower are discarded.

If a boss causes one of their own towers to fall: that git falls over. Knock the model over on its ass. If that happens during a git’s activation, their activation is over. 

If a boss causes anyone else’s tower to fall, through clumsiness or deliberate sabotage, that model suffers a moment of lucid clarity and sobers up: their tower dice are all discarded, but they remain standing. (Basically: don’t knock other player’s towers over.)

If a rolled die causes a tower to fall, the boss that rolled that die has knocked that tower over. If a stray die from a tumbling tower causes another tower to fall, the boss that caused the initial cascade is the one that knocked that other tower over.

### Fallen Models
A fallen model can’t be picked to activate until they are back on their feet again. 

Fallen models don’t have towers and can’t be given any new tower dice until they are back on their feet.

### Take a Swig
After a model activates, they take a swig: add a D6 to the top of their tower. 

### Damage
When one of your models gets damaged, for each point of damage received, your opponent gives you a D6 to add to your damaged model’s tower.

> [!TIP]
> _The tower in SPACE GITS represents drunkenness and bruises. Your tower could represent anything you like: fear, stress, excitement, arcane energy, loss of control, heat. You could even change the tower to work in reverse: with each model starting with a tower of whatever number of dice and wanting to keep them for whatever reason; maybe they provide power, boost stats, or are the victory system (like some kind of egg-and-spoon race...)._

## Weapons
Weapon are either Shooting Weapons, and used during Shoot Actions, or Fighting Weapons, used during Fights.

### Shooting Weapons
Shooting Weapons have the following stats:

* **Range**: The maximum distance a bullet from this weapon will travel.
* **Bullet Dice**: The dice rolled when shooting with this weapon.
* **Weak/Big Damage**: The damage values that apply when this weapon hits another model.

### Fighting Weapons

Fighting Weapons have the following stats:

* **Thump Dice**: The dice rolled when thumping with this weapon.
* **Weak/Big Damage**: The damage values that apply when thumping another model with this weapon.

## Set Up

### Table
Clear a play area roughly 3-foot by 3-foot and set up plenty of terrain. 

> [!TIP]
> _The table setup is something that you can freely experiment with, and potentially you wlil want to vary from scenario to scenario._

### Loot Tokens
Each boss drops 6 Loot Tokens onto the table from a decent height. 

Put one more Loot Token in the middle as a tie-breaker. 

> [!TIP]
> _The loot tokens aren't essential, but the do provide a randomly distributed set of focus points for the game. You could alter the placement of these loot tokens, or replace them with a different objective system, as you wish._

### Deployment
Randomly determine a First Player.

Starting with the First Player, take turns to place one model at a time anywhere in play, at least 4” from all Loot Tokens and enemy models.

The First Player activates the first model.

> [!TIP]
> _The deployment process is something that you can freely experiment with, and potentially want to vary from scenario to scenario._

### Start the Clock
Once all the models are deployed, start a timer for 30 minutes and start the game. 

> [!TIP]
> _Varying the timer length, or remove it, to change the length or remove the time pressure of the game._


## Activating Models
We take turns activate one model each, starting from the First Player.

There are no game rounds, we just keep activating models until one of us has had enough and the game ends.

When it is your turn to activate a model, you choose one of your models (but not a fallen one) and activate it.

When you activate a model, they do one or two different actions out of: Shoot, Scoot and Boot (in any order). 

You don’t have to activate your models in rounds, if you want to keep activating the same model turn after turn: that is allowed.

> [!TIP]
> _Pretty much every word in this section could be modified without breaking the game engine._


## Scoot Action
When a model takes a Scoot Action, roll their Move Dice into the play area.

> [!TIP]
> _You can vary the number and type of dice thrown as Move Dice._
 
Resolve one Move Die at a time in any order

> [!TIP]
> _You could force the player to resolve the Move Dice in ascending order, or starting with the dice closest to them, or something else._
  
When you resolve a Move Die you move your model directly towards that dice a number of inches equal to the value of that dice and then discard it. 

You have to move the model the full distance towards the Move Die if you can.

> [!TIP]
> _You could replace this with "You do not have to move the model the full distance towards the Move Die if you can." I.e. You could force the model to move the full rolled distance towards the Move Die, or permit them to stop at any point during their scoot._

You have to use all your move dice. 

> [!TIP]
> _You could replace this with "You do not have to use all your move dice, and can discard any of your Move Dice without resolving them." I.e. You could force the player to resolve all dice, or permit them to only resolve the ones they want to, and discard the others._

As you move the model, make sure the little tower of dice is touching them at all times. If any of the dice fall, so does the model. (See "The Tower".)

## Looting
Each boss has a collection of Loot Tokens, called their Stash.

If you bump into a Loot Token while moving, you stop moving and pick it up.

Loot Tokens that you pick up go into your Stash.

## Shoot Action
When a model takes a Shoot Action, it selects one of its shooting weapons and gathers a number and type of bullet dice indicated by the shooting weapon's stats.

Roll your bullet dice into the play area. 

Each bullet travels from the shooting model in a straight line directly towards one of the bullet dice a number of inches equal to the gun’s range, hitting the first thing in its path (ignoring dice and fallen models). 

If the thing that is hit is a model, compare the value of the bullet dice to the toughness of that model. If the rolled value meets or beats the toughness, the unlucky model suffers big damage from the gun. If the value is lower than the model’s toughness, they suffer weak damage.

## Fighting
If two opposing models end up in contact, the current activation ends and a fight breaks out.

When two models fight, their bosses count 3, 2, 1… and then throw one of either 👊 Thump, 🖐️ Shove or 🤏 Pinch with their hands.

The active model resolves their effect first, then the passive model does. If it isn’t clear who the active model is, it is the model who’s movement (or who’s standing up) caused the fight to break out.

Once the throw is resolved, if the two models are still in contact (and both are still standing) they fight again, and continue to do so until they are separated or one falls.

### Thump
👊 Thump is a fist (like "rock" or "stone"). 

If a boss throws 👊 Thump, their model Thumps the other model, unless the other boss threw 🖐️ Shove.

To Thump: roll all your fighting weapons’ thump dice. Do big damage with each dice that equals or beats the other model’s toughness, and weak damage with the others.

### Shove
🖐️ Shove is a flat hand (like "paper").

If a boss throws 🖐️ shove, the other model is pushed back 3”, unless their boss threw 🤏 Pinch. 

The shoved model is moved by its boss, along with their tower. 

The shoved model is moved directly away from their opponent. 

If rhe shoved model is shoved into some terrain, they suffer 1 damage.

### Pinch
🤏 Pinch is the thumb and index finger extended and held together (like an "OK" sign, or "scissors" but using your thumb).

If a boss throws 🤏 Pinch, they take 1 Loot Token from the other model’s boss, unless the other boss throws 👊 thump.

> [!TIP]
> _When both bosses throw Pinch, as they just swap a cap and nothing happens. This is a place that needs improvement, but I haven't improved it yet._

## Boot Action
When a model takes a Boot Action, the effect depends on what they are in contact with.

### Put the Boot In
If a model is in contact with a fallen enemy model, they take a Boot Action to "put the boot in": they take 1 Loot Token from the fallen model’s boss.

### Boot Up
If a model is in contact with a fallen friendly model, they can boot them up: the booted model stands up. 

When a model stands up, put it anywhere at least touching the area where they were just lying. If you place them into contact with an enemy, the current activation ends and a fight breaks out.

## Leg It
When it is your turn to activate, you can leg it instead.

When it is your turn to activate, if you have nothing left that you can activate, you have to leg it.

When you leg it: any of your models that are within 6” of an enemy model are replaced with a Loot Token from your stash, then remove the rest of your models and you are out of the game.

## Times Up
When the 30 minute timer is up, models can no longer take Boot Actions. (That means that fallen models stay down).

> [!TIP]
> _When the timer is up, everyone get one more activation, and then the game ends._

## Game End & Victory
The game ends when only one boss is still playing. 

At the end of the game, the last remaining boss scoops up any in-play Loot Tokens. 

The winner is the boss that walked away with the most new Loot Tokens this game.

> [!TIP]
> _The victory conditions could be anything, and you could easily vary them from scenario to scenario._

# Opportunities for elaboration
This SRD doesn't contain rules for terrain, or vehicles, or different types of models. It doesn't contain special rules for weapons, or any factions. It doesn't contain any scenarios, beyond a single default "loot the tokens" play mode. These are all open design spaces for you to inject your own flavour and fantasy on top of the system.

Hack this system to pieces, superglue it back together in whatever shape you like. Playtest.

If you use **Riot Dice** for anything, [let me know](https://planetsmashergames.com/discord/)
