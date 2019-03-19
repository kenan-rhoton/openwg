# Reglas básicas

## Turn structure

A *Turn* has 4 *Phases*:

1. Movement: players take turns in moving units that haven't moved this turn.
	- A unit may decide to Run or Retreat (double move but can't shoot or fight that turn)
	- A unit may decide to Charge (double move that must end in combat but can't shoot)
2. Ranged: players take turns in shooting with units that haven't shot this turn.
3. Melee: players take turns attacking with units locked in combat.
4. Leadership: players count casualties and use special skills.

At any point, one of the players may elect to *Stop* as his action for the phase.
If a player has no eligible units to choose in a phase, he must elect to *Stop*.
The first player to choose to *Stop* will act first in the following phase.
When all players have elected to *Stop*, the game advances to the next phase.

## Units and Models

A unit is a group of models. Whenever you need to find the value of any model's characteristic, if it doesn't have one, please use it's unit's characteristic instead.

## Attacks and damage

When a unit attacks another unit (whether it be the *Ranged* or the *Melee* phase), first select which models within range of the unit will attack it.

First, roll a die for each model attacking the unit and compare it to its *Precision*: if the roll is equal or lower, it scores a **HIT**.
Then, for each **HIT**, roll dice equal to the model's *Damage* and compare it to the target unit's *Armor* minus the attacker's *Pierce*: if the roll is higher, it scores a **WOUND**.
Keep track of the number of **WOUNDS** suffered by each unit throughout the turn.

A unit may declare multiple units as its target.
If it does, declare which models within range attack which unit and then resolve the attacks separately.

# The Turn

## Action Phase

Players take turns activating units that haven't yet activated.

They may take the following Actions:

- Move: A unit must not be in combat to Move. To Move a unit, move each of the models a distance up to the model's Move characteristic. 
- Run: A unit must not be in combat to Run. To Run a unit, take the Move action twice.
- Charge: A unit must not be in combat to Charge. To Charge a unit, it must move in a straight line into combat. This move may be of up to twice its Move characteristic. It may then immediately Fight.
- Shoot: Attack with their Ranged Weapons. If the unit is in combat it must Attack a unit it's in combat with. If it isn't, it may Move before or after Shooting.
- Fight: A unit must be in combat to Fight. Attack with that unit's Melee Weapons. You may make an Adjust move of up to 3" with that unit. This move cannot take you out of combat.

When starting the move, the player may declare the unit is *Running*.
If they do so, the unit may move twice its move characteristic, but it may not shoot or fight in the *Ranged* and *Melee* phases.

A player may also declare that a unit is *Charging*.
That unit may move twice its move characteristic but must end its move in combat.

Finally, as a special case, a player may select a unit that is in combat and declare it is *Retreating*.
Resolve this move just as if the unit had been declared *Running*.

## Ranged

Players take turns shooting with units that haven't done so yet and haven't *Run*, *Retreated* or *Charged*

## Melee

Players take turns fighting with units that haven't done so yet and haven't *Run*, *Retreated* or *Charged*

## Leadership

The Leadership Phase consists of a series of steps:

1. Leadership Skills (Magic/Prayers/etc.)
2. Resolve Wounds
3. Test Morale

### Leadership Skills

This will be shown in the model's rules. Rules for Magic and Prayers are in the first section.

### Resolve Wounds

Each player clears the wounds from a unit by damaging models.
Once a player has started damaging a model they must continue to do so until that model is slain.
A model is slain when it suffers damage equal to its Health characteristic.
A slain model is removed from the game.

### Test Morale

Every unit that had  models slain must make a Morale test.
To do so, roll a die for the unit and add the amount of models slain in the unit this turn.

If the amount exceeds its Bravery, a number of models equal to the difference flee from the battle and are removed from the game.

# Converted Units

## Fyreslayers

Throwing Axes (Ranged):
- Range: 8"
- Damage: 1
- Precision: 3
- Pierce: 0

Each unit of Fyreslayers may, once per battle, use the Throwing Axes Ranged Attack at the beginning of a Charge move.


### Vulkite Berzerkers (120/30)

- Size: 10
- Movement: 4"
- Bravery: 7
- Armor: 2
- Health: 1

Melee:
- Range: 1"
- Damage: 2
- Precision: 3
- Pierce: 0

Loadouts:
- War-picks and Shields: +1 Pierce in Melee, +1 Armor when they haven't charged
- Handaxe and Shields: +1 Armor when they haven't charged
- Pair of Handaxes: Reroll failed Melee Precision rolls

Special:
- When resolving wounds, roll a die for each wound. On a 1 ignore the wound. 2 if at least 10. 3 if at least 20.
- When charging and holding shields, choose a unit within 8" and roll a die for each model in this unit with Shields. On a 1 deal a wound.
- A model in this unit may be a hornblower, granting +2" Movement when Charging.
- The leader is the Karl. Double the Karl's damage.

### Hearthguard Berzerkers (100/30@480)

- Size: 5
- Armor: 2
- Movement: 4"
- Bravery: 8
- Health: 1

Melee:
- Range: 1"
- Damage: 1
- Precision: 4
- Pierce: 0

Loadouts:
- Broadaxes: +1 Damage and +1 Pierce in Melee
- Flamestrike Poleaxes: Roll a die for every Melee hit. Every 4 or less inflicts a WOUND.

Special:
- When resolving wounds, roll a die for each wound. On a 1 ignore the wound. On a 3 if within 10" of a Fyreslayer HERO.
- The leader is the Karl. +1 to the Karl's damage.


## Stormcast Eternals

### Evocators (200/20)

- Size: 5
- Armor: 3
- Movement: 5"
- Bravery:  8
- Health: 3

Melee:
- Range: 1"
- Damage: 4
- Precision: 4
- Pierce: 0

Loadouts:
- Tempest Blade and Stormstave: +1 Pierce in Melee
- Grandstaves: +2 Damage and +1" Range in Melee

Special:
- Reroll 6s on Armor rolls in the Ranged phase.
- After this unit attacks, choose an enemy unit within 3" and roll 2 dice for each model in this unit. On a 3 deal a WOUND.
- The leader is the Evocator-Prime. +2 damage.
- This unit is a WIZARD as long as it has 2 or more models. It can cast Empower.

Empower:
- Cast at 6
- Pick a friendly unit within 12" of the caster. Until your next Leadership phase, reroll successfull Armor rolls for HITs made by that unit.

# Unit builder

## Health Ranks

you get a 2 point discount for each extra health per model

1. 5 models with 1 health
2. 10 models with 1 health OR 5 models with 2 health
3. 12 models with 1 health OR 6 models with 2 health OR 4 models with 3 health OR 3 models with 4 health
4. 15 models with 1 health OR 5 models with 3 health OR 3 models with 5 health
5. 20 models with 1 health OR 10 models with 2 health OR 5 models with 4 health

## Units

### Troops

- Base cost: 5
- Health Rank: 2/5
- Armor: 1/2
- Movement: 4"/10"
- Bravery: 5/10

Melee (basic):
- Range: 1"/2"
- Damage: 2/5
- Precision: 2/4
- Pierce: 0/1

Ranged Sidearm (upgrade):
- Range: 8"/16"
- Damage: 2/4
- Precision: 2/4
- Pierce: 0

Cost 1: +1 Movement, +1 Bravery
Cost 2: +1 Precision, +1 Armor, +1 Damage, +1 Health, Standfast (take Hold action out of combat for +1 Armor), +1 Melee Range, +4 Ranged Range
Cost 3: +1 Shrug (ignore wounds), +1 Melee Pierce, Ranged Sidearm

### Breakers

- Base Cost: 12
- Unit Health: 3/4
- Armor: 1/2
- Movement: 5"/12"
- Bravery: 7/10

Melee:
- Range: 1"/3"
- Damage: 3/8
- Precision: 3/5
- Pierce: 0/2

Ranged Sidearm (upgrade):
- Range: 8"/16"
- Damage: 2/5
- Precision: 2/4
- Pierce: 0/1

Cost 1: +1 Movement, +1 Damage, +1 Melee Range
Cost 2: +1 Precision, +1 Pierce, Ranged Sidearm, +4 Shooting Range, +3 Movement
Cost 3: +1 Armor, +1 Health, Frenzy (can Fight twice), +2 Bravery

### Rocks

- Unit Health: 3
- Armor: 2
- Movement: 4"
- Bravery: 7

Melee:
- Range: 1"
- Damage: 2
- Precision: 2
- Pierce: 0

Cost 1: +2 Movement, +1 Damage, +1 Range (+4 if Ranged), +1 Precision, +1 Pierce
Cost 2: +2 Movement, +1 Bravery, +2 Damage, +1 Health, +1 Armor, Ranged Sidearm
Cost 3: +1 Health, +2 Movement, +2 Bravery, +2 Damage, +1 Pierce, +1 Precision

### Shooter

- Unit Health: 1
- Armor: 1
- Movement: 4"
- Bravery: 5

Melee:
- Range: 1"
- Damage: 2
- Precision: 2
- Pierce: 0

Ranged:
- Range: 12"
- Damage: 2
- Precision: 2
- Pierce: 0


Cost 1: +4 Range (Ranged), +2 Bravery, +1 Damage, +1 Precision, +1 Armor
Cost 2: +2 Movement, +1 Pierce, +4 Range (Ranged), +2 Unit Health
Cost 3: +6 Range (Ranged), +3 Movement, +3 Bravery, +2 Damage, +1 Shrug, +1 Armor

## Solos

# Original Units

## The Seekers

### Spearhead (Troop 5+1+3+2+2+2+2+3 = 20)

- Size: 10
- Armor: 2
- Movement: 5"
- Bravery: 8
- Health: 1

Melee:
- Range: 2"
- Damage: 2
- Precision: 3
- Pierce: 1

Special: Standfast

### Hunters (Breaker 12+2+2+3+2+2+2+1+1+1=28)

- Base Cost: 12
- Size: 10
- Health: 1
- Armor: 1/2
- Movement: 11"/12"
- Bravery: 9/10

Melee:
- Range: 1"/3"
- Damage: 5/8
- Precision: 4/5
- Pierce: 0/2

Ranged:
- Range: 8"/16"
- Damage: 3/5
- Precision: 3/4
- Pierce: 0/1
