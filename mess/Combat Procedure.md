# Combat

**NPC Stats: Name - Move # (Special), Defense # (description), Danger #d/Attack Skill #, Hits #, Special**

**Example:** *Beetle Clan Assassin - Hits 3, Defense 3 (hidden mail shirt), Move 1 (Climb), Danger 2d/Attack Skill 2 (Steel, Melee, Poisoned Scimitar), Special: Wearying Poison (targets lose 2 momentum per strike)*

- Hits: The number of successful strikes this NPC can endure before it is killed or disabled.
- Defense: The number added to the momentum cost for a PC to Strike or Reposition against this NPC, and a qualitative description of the source(s) of this protection (armor, carapace, mobility, etc.)
- Move: How many distance categories the NPC can move relative to the closest PC on its turn, and any special movement methods available.
- Danger: The number of times a PC must roll their armor die each time they are struck by this NPC.
- Attack Skill: The number subtracted from each one of a struck PC's armor die rolls, followed by the material/range/name of this NPCs means of attacking
- Special: The NPC's unusual abilities. Defined briefly, or below the NPC stat line if necessary.

**PC Statblock Example**\
Diaghilev (Mercenary 1) - Might 0, Grace 2, Grit 0, Charm 2, Lore 0, Fate 2 (1d8); P 1d10/M 1d6\
Weapons/Shield: Yatagan (Steel, Melee, Slashing), Throwing Hatchets (Ud6, Steel, Near, Piercing); Iron Buckler (Base UD4)\
Armor Ud6+0 (Mail Shirt); Max Hits: 3\
Momentum Gain/Current: 1d10+2 / 0 (-2 EoR)\
Stamina (10): 0

| Class | Physical Discipline Die | Mental Discipline Die |
| :---: | :---: | :---: |
| Berserker | 1d12 | 1d4 |
| Mercenary | 1d10 | 1d6 |
| Wanderer | 1d8 | 1d8 |
| Cultist | 1d6 | 1d10 |
| Scholar | 1d4 | 1d12 |

---

**Sometimes you've just gotta chop heads. Combat basically works like this:**

1. When combat begins, each player rolls a discipline die + Grace to generate **momentum**. Roll your better discipline die if you saw the threat coming; roll your worse discipline die if it was a surprise. The result of your roll is both your starting momentum value and your **initiative score**. NPCs have initiative scores equal to their Attack Skill + 3, but NPCs do not use momentum. Turn order proceeds from highest to lowest inititive score.

2. NPCs may do all of the following things on their turns:
- Move OR Interact
	- **Move:** An NPC can move a number of distance steps equal to their Move score. Special methods of movement, such as climbing or flying, will have their own Move scores.
	- **Interact:** As described below.
- Strike OR Reposition OR Use An Ability
	- **Strike:** NPCs do not make attack rolls; rather, PCs make defense rolls. See below.
	- **Reposition:** An NPC automatically repositions themselves against another NPC or PC, but a PC immediately gains momentum equal to 4 minus the NPC's attack skill (minimum 0).
	- **Use An Ability:** Resolve per the description of the ability being used.

3. When your turn begins:
- Mark a Stamina tally. Your Stamina is equal to 10 + Grit. If you have Stamina tallies equal to your Stamina score, erase all your Stamina tallies and fill an item slot with EXHAUSTED. 
	- The EXHAUSTED item slot can't be used until you rest, at which point all EXHAUSTED item slots are restored.
- Spend momentum to take actions; costs in momentum are written as **[number]M.**

4. If you're at the right range to Strike your target and you have the momentum to do so, it happens. When a foe is out of hits, they're dead (or disabled, if you prefer; see "Strike to Disable").

5. If an enemy Strikes you, you can pay the momentum (3M or more) to actively defend youself by Parrying (high risk/reward), Dodging (moderate risk/reward), or Blocking (low risk/reward but requires a shield that can degrade over time). If you are unable or unwilling to actively defend, you can passively defend yourself with a parry, dodge, or block (1M), even if this would leave you with negative momentum, although negative momentum applies as a penalty to all defense rolls. You can also decide to forgo self-defense and rely entirely on your armor.
- Parry: 
	- Note: Steel can only parry steel; magic can only parry magic. 
	- Roll: Discipline Die + Might (physical) or Lore (magic) + extra momentum spent **VERSUS** 7 + Foe Attack Skill
	- Failure: Critically struck by attack (the strike gains +1d Danger)
	- Success: Deflect incoming attack and riposte (gain 4 momentum and may immediately Strike)
- Dodge: 
	- Roll: Physical Discipline Die + Grace + extra momentum spent **VERSUS** 7 + Foe Attack Skill
	- Failure: Partial avoidance; any armor die rolls receive a bonus equal to the extra momentum spent on the Dodge active defense
	- Success: Attack successfully dodged.
- Block: 
	- Note: Blocking requires a ready shield. Steel and magic can block both themselves and each other.
	- Roll: Shield armor die + Grit (physical) or Lore (magic) + extra momentum spent **VERSUS** 2 + Foe Attack Skill
	- Failure: Struck by attack.
	- Success: Attack blocked. Immediately roll shield armor die.

6. If you fail or don't bother to defend yourself and the enemy successfully Strikes you, roll your Armor Die + Grit. Dangerous enemies will impose a negative modifier on this roll; VERY dangerous foes will make you roll more than once. If you roll a total of 1 or lower on your Armor Die, the enemy's blow struck true and you take a hit. Additionally, your armor die decreases one step. You can endure a maximum number of hits equal to 2 + 1/2 your level (rounded down) + Grit. Hits beyond this limit are tremendously dangerous.

Starting Armor Die is deterined by the type of armor worn. When you take a hit, reduce the Armor Die by one step (Ud8 -> Ud6 -> Ud4 -> 1 -> 0). End of Round penalties to momentum do not change as armor is damaged.
- No Armor: No Armor Die; all successful strikes are hits.
- Leather: Ud4
- Chain: Ud6
- Plate: Ud8

7. For every hit you suffer beyond your maximum limit, you roll a cumulative 1d6 on the DIRE WOUNDS table. Although effects differ by the type of damage inflicted, generally...
- 1-5 is Very Sad (Temporary reduction of stats)
- 6-10 is Disabled (Knocked senseless for at least 10 minutes)
- 11-15 is Disfigured (Permanent cosmetic damage--missing teeth/ear/nose/unimportant fingers)
- 16-20 is Mauled (Limb severed; fatal if untreated)
- 21-25 is Instant Death (in various flavors)
- 26+ is Violent Death (A death so shocking it afflicts your allies or hazards the battlefield)

8. Resolve any End of Round effects:
- Resolve spells and abilities that have an End of Round component.
- Resolve penalties to momentum from armor.
	- No Armor: No End of Round momentum penalty
	- Leather: -1 momentum at End of Round
	- Chain: -2 momentum at End of Round
	- Plate: -4 momentum at End of Round

9. Begin the next round. Everyone rolls initiative again, adds the new value to their current momentum count, and those values are used to determine turn order. Repeat these steps until there's nobody left who wants to keep fighting.

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

Striking to Disable: If you want to merely knock out or disable your target, your Strike costs one additional momentum due to the difficulty of pulling your punches. You must declare your intent to Strike to Disable before paying the momentum cost and learning the result of your blow. If you didn't pay the extra momentum cost and your Strike removes your target's final hit, they're slain despite your best intentions.

### Move
Change your distance relative to something and/or someone else.

***Why would I do this?***
- Some attacks function best--or only work at all--at a specific range relative to the target.

#### Distances and Positions:
- **Intimate**: Near enough to headbutt.
- **Melee**: Kicking or spitting distance.
- **Near**: Talking distance. Across a room.
- **Far**: Singing or shouting distance.
- **Distant**: Just far enough to see on a clear day.

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
- Active Defense: 3M or more OR 2M or less (see description)

### Active Defense
Defend yourself against an attack with a Parry, Dodge, or Block. 
- You may spend additional momentum beyond the minimum of 3M on an active defense. Your Parry, Dodge, or Block roll receives a bonus equal to momentum spent beyond the minimum of 3M.
- You may spend less than 3M on your active defense, but you suffer a penalty equal to the difference between 3M and the momentum spent. You may attempt an active defense even if you have negative momentum; resolve your defense with a penalty equal to the difference of 3 and your current negative momentum, then reduce your current momentum by 1M, even if your momentum would become or was already negative.

*Example: Bretolomeo has a Physical Discipline Die of 1d10 and a Grace of 1. A Seething Cultist with an Attack Skill of 2 hurls a magical gout of boiling blood at him, and Bartolomeo decides to spend momentum on an Active Defense--a Dodge. In addition to the minimum requirement of 3 momentum, Bartolomeo spends an additional 2 momentum, as getting covered in boiling blood sounds deeply unpleasant. Bartolomeo's Dodge roll is 1d10 (his Physical Discipline Die) + 1 (Grace) + 2 (momentum spent beyond the minimum of 3) - 2 (the Seething Cultist's Attack Skill). Bartolomeo rolls 1d10+1.*

*Example: Later, Bretolomeo has been worn down by splashes of boiling blood and has only 1 momentum remaining. The Seething Cultist attacks him again, and Bretolomeo attempts to Dodge. He spends his remaining 1M, and his Dodge roll is 1d10 (his Physical Discipline Die) + 2 (Grace) - 2 (the difference between his 1M spent and the requirement of 3M) - 2 (the Seething Cultist's Attack Skill). Bartolomeo rolls 1d10-2.*

*Example: Bretolomeo is in deep trouble. After defeating the Seething Cultists, pressgang recruiters for the Aneman navy accost him as he limps back into town. After the initial furious ambush, Bartolomeo finds himself with -3 momentum. The Aneman brute swings his cudgel, and Bartolomeo does his best to roll under the blow, attempting to Dodge. His Dodge roll is 1d10 (his Physical Discipline Die) + 2 (Grace) - 6 (the difference of 3 and his current momentum) - 1 (the Aneman Brute's Attack Skill). Bartolomeo rolls 1d10-5.*