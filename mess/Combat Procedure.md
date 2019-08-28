# Combat

**NPC Stats: Name - Defense #, Attack Skill #/Danger #d, Hits #, Special**

**Example:** *Master Assassin - Move 1, Attack Skill 2/Danger 2d, Defense 3, Hits 3, Special: Wearying Poison (hit targets lose 2 momentum)*

- Move: How many distance categories the NPC can move relative to the closest PC on its turn.
- Attack Skill: The number subtracted from each one of a Struck PC's armor die rolls.
- Danger: The number of times a PC must roll their armor die each time they are struck by this NPC.
- Defense: The number added to the momentum cost for a PC to Strike or Reposition against this NPC.
- Hits: The number of successful Strikes this NPC can endure before it is killed or disabled.
- Special: Unusual abilities the NPC has. Defined below the NPC stat line if necessary.

---

**Sometimes you've just gotta chop heads. Combat basically works like this:**

1. Everyone rolls initiative. You roll your good die if you saw it coming; you roll your bad die if it's a surprise. Good dice and bad dice aren't *that* far apart; sometimes the foeman's bad day is better than your best.

2. At the start of your turn, roll your good discipline die to generate **momentum**. Then, spend that momentum to do stuff; costs in momentum are written as **[number]M.**

3. If you're at the right range to Strike your target and you can afford the momentum to do it, it happens. When a foe is out of hits, they're dead (or disabled, if you prefer; see "Strike to Disable").

4. If an enemy Strikes you, you can pay the momentum to actively defend youself by Parrying (high risk/reward), Dodging (moderate risk/reward), or Blocking (low risk/reward but requires a shield that degrades over time). If you can't or don't want to actively defend, you can passively defend by paying 1 momentum, even if this leaves you with negative momentum. You can also decide to forgo self-defense and rely entirely on your armor.
- Parry: 
	- Note: Steel can only parry steel; magic can only parry magic. 
	- Roll: Discipline Die + Might (physical) or Lore (magic) + extra momentum spent - Enemy Attack Skill; success on a 7 or higher.
	- Failure: Critically struck by attack (the strike gains +1d Danger)
	- Success: Deflect incoming attack and riposte (gain 4 momentum and may immediately Strike)
- Dodge: 
	- Roll: Physical Discipline Die + Grace + extra momentum spent - Enemy Attack Skill; success on a 7 or higher.
	- Failure: Partial avoidance; any armor die rolls receive a bonus equal to the extra momentum spent on the Dodge active defense
	- Success: Attack successfully dodged.
- Block: 
	- Note: Blocking requires a ready shield. Steel and magic can block both themselves and each other.
	- Roll: Shield armor die + Grit (physical) or Lore (magic) + extra momentum spent - Enemy Attack Skill; success on a 2 or higher.
	- Failure: Struck by attack.
	- Success: Attack blocked. Immediately roll shield armor die.

5. If you fail or don't bother to defend yourself and the enemy successfully Strikes you, roll your Armor Die. Dangerous enemies will impose a negative modifier on this roll; VERY dangerous foes will make you roll more than once. If you roll a 1 or lower on your Armor Die, the enemy's blow struck true and you take a hit. Additionally, your armor die decreases one step. You can endure a maximum number of hits equal to 2 + 1/2 your level (rounded down) + Grit.

6. For every hit you suffer over your maximum, you roll a cumulative 1d6 on the DIRE WOUNDS table. Although effects differ by the type of damage inflicted, generally...
- 1-5 is Very Sad (Temporary reduction of stats)
- 6-10 is Disabled (Knocked senseless for at least 10 minutes)
- 11-15 is Disfigured (Permanent cosmetic damage--missing teeth/ear/nose/unimportant fingers)
- 16-20 is Mauled (Limb severed; fatal if untreated)
- 21-25 is Instant Death (in various flavors)
- 26+ is Violent Death (A death so shocking it afflicts your allies or hazards the battlefield)

## Initiative

All actors participating in combat roll initiative.
- All actors **aware of danger** roll their **highest** discipline die + Grace. 
- All actors **surprised by danger** roll their **lowest** discipline die + Grace.

This roll becomes the actor's starting momentum. Actors take their turns in the order of their starting momentum, from highest to lowest.

Once all actors have taken a turn, all actors still participating in combat roll initiative again and add the result to their current momentum. Actors take their turns in the order of their current momentum, from highest to lowest.

An actor may spend as much momentum on their turn as they wish, as long as the action taken would not leave them with negative momentum.
- Passive Defense is an exception; this action can result in a negative momentum count.
- If an actor begins their turn with negative momentum, they may not act on their turn until they have positive momentum.

## ACTIONS AND COSTS DURING YOUR TURN: 
- Strike: 4M + Target Defense
- Move: 3M
- Reposition: 2M + Target Defense
- Interact: 2M
- Call Out: 1M
- Use Ability: Per ability description

### Strike
Use your weapon (magical or mundane) to inflict harm on a target.

An actor's defense value adds to the momentum cost of attempting to Strike them.
- *Maissa strikes at a subterranean turtle knight. The turtle knight has a Defense of 2; normally, Maissa's strike would cost 4 momentum, but the knight's Defense of 2 raises the cost to 4 + 2  = 6 momentum.*

Striking to Disable: If you want to merely knock out or disable your target, your Strike costs one additional momentum due to the difficulty of pulling your punches. You must declare your intent to Strike to Disable before paying the momentum cost and learning the result of your blow. If you didn't pay the extra momentum cost and your Strike removes your target's final hit, they're slain despite your best intentions. Combat is dangerous.

### Move
Change your distance relative to something and/or someone else.

***Why would I do this?***
- Some attacks function best--or only work at all--at a specific range relative to the target.

#### Distances and Positions:
- **Intimate**: Close enough to headbutt.
- **Near**: Close enough to spit on.
- **Far**: Close enough to hear angry shouting.
- **Distant**: A couple of football fields at least.

### Reposition
Move to a superior tactical position relative to a single opponent, such as forcing your foe to fight with their back to a pit.

An actor's defense value adds to the momentum cost of attempting to Reposition against them.

***Why would I do this?***
- Some abilities require the user to be in a superior position relative to their target.

### Interact
Retrieve and use an item from a pocket or bag. Alternatively, interact with the environment--open or close a door, pull a lever, flip a table, etc.

### Call Out
Utter anything more complicated than a shout of warning with the intent that a named ally hears and understands you.
- The ally whose you name you call immediately gains 1M. An ally can only gain 1M from Call Out actions per turn.

### Use Ability
Some actors have special abilities or talents. The momentum cost to use them will be listed in that ability's description.

## ACTIONS AND COSTS DURING ANOTHER ACTOR'S TURN: 
- Active Defense: 3M or more
- Passive Defense: 1M

### Active Defense
Commit significant effort to a Parry, Dodge, or Block against an attack. You may only take this action if you have the momentum to spend on it. You may spend additional momentum beyond the minimum of 3 on your active defense. Your Parry, Dodge, or Block roll receives a bonus equal to momentum spent beyond the minimum of 3.
- *Example: Bretolomeo has a Physical Discipline Die of 1d10 and a Grace of 1. A Seething Cultist with an Attack Skill of 2 hurls a magical gout of boiling blood at him, and Bartolomeo decides to spend momentum on an Active Defense--a Dodge. In addition to the minimum requirement of 3 momentum, Bartolomeo spends an additional 2 momentum, as getting covered in boiling blood sounds deeply unpleasant. Bartolomeo's Dodge roll is 1d10 (his Physical Discipline Die) + 1 (Grace) + 2 (momentum spent beyond the minimum of 3) - 2 (the Seething Cultist's Attack Skill). Bartolomeo rolls 1d10+1.*

### Passive Defense
Parry, Dodge, or Block an attack with minimal effort. **You may spend momentum to take this action even if it would result in holding negative momentum,** but your Parry, Dodge, or Block roll suffers a penalty equal to your negative momentum.