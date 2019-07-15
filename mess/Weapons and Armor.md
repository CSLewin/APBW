# Weapons, Damage Types, Shields, Armor, Damage Reduction

## WEAPONS

All weapons have the following qualities:
- Size (Light, One-Handed, Two-Handed)
- Base Damage Die (1d4, 1d6, 1d8, 1d10, 2d6)
- Range (Whisper, Speak, Shout)
- Damage Type (Bludgeoning, Piercing, Slashing)
- Weight (0 or more inventory slots)
- Modifications (See Below)

By default, all weapons are one-handed, deal 1d8 damage, and take up one inventory slot.

Ranges for weapons and magic fall into three categories which describe the maximum distance at which the weapon or spell is effective: 
- **Whisper**
- **Speak**
- **Shout**

Weapons wielded in melee combat add Might to attack and damage rolls.  
Weapons wielded in ranged combat add Grace to attack and damage rolls.  
All magical fighting techniques (melee or ranged) add Lore to attack and damage rolls.

Damage chain: (minimum) 1d4 <--> 1d6 <--> 1d8 <--> 1d10 <--> 2d6 (maximum)

A weapon quality may only be applied to a weapon once.

Weapon Origin:

	Aneman/Pirran/Jhil: No mechanical changes, although each country's style of manufacture and decoration is set apart by details both subtle and overt.
	Temenite: Constructed entirely of nonmetallic materials equivalent in weight and function to steel.
	Imperial: Durable but heavy. +1 slot; may ignore the first strike suffered by the armor/weapon each session.
	Chernikan: Light but brittle. -1 slot; first strike suffered by the item counts as two strikes, each of which must be repaired.

Weapon Modifications:

	Light: This weapon is particularly easy to handle and quite suitable for dual-wielding. -d, -1 slot
	Heavy: Requires two hands to wield. +d, +1 slot
	Long: The weapon requires two hands to wield and is long enough to strike enemies up to 10 feet away. -d, +1 slot
	Defensive: Any round in which this weapon is wielded but not used to attack, the weapon provides +1 AC. +1 slot
	Vicious: The weapon bears cruel hooks, barbs, or serrations. Handle with care. +d, +2 slots

### Critical Hits
A critical hit occurs when an attacker rolls a natural 20. 
- First, the attack automatically hits regardless of target's relevant defense. 
- Second, the attack's damage is increased to the maximum value possible for the attack plus an additional roll of the attack's damage dice and modifiers.
	- An attack that would normally do 1d8+3 damage would deal 11 + 1d8+3 damage on a critical hit.
	- An attack normally dealing 2d6+3 damage would deal 15 + 2d6+3 damage on a critical hit.
- Third, the type of damage inflicted determines an additional critical effect.

### Damage Types
- Bludgeoning: Ignores an amount of target's damage reduction equal to the wielder's Might score.
	- Critical Effect: The target is battered away from the attacker in a straight line with a distance equal to 5 feet times the attacker's Might or Grace score (attacker's choice).
- Piercing: Add the wielder's Might or Grace score to the attack roll twice, rather than once.
	- Critical Effect: The target suffers a debilitating wound that inflicts the attacker's level in damage at the end of every round until any healing is applied or the target dies. This ongoing damage ignores the target's damage reduction. Multiple instances of ongoing damage from piercing critical hits may simultaneously exist on a target and must be individually addressed.
- Slashing: Add the wielder's Might or Grace score to the damage value twice, rather than once.
	- Critical Effect: The target's armor immediately suffers two strikes in addition to any strikes normally inflicted.

### Dual-Wielding: 
Fighting with more than one weapon simultaneously is a difficult but impressive technique. When dual-wielding, the attacker makes a single attack roll representing an attempt to strike with both weapons. While dual-wielding, the total number of inventory slots occupied by all wielded weapons are applied as a penalty to the wielder's attack roll. On a successful attack made while dual-wielding, the attacker rolls damage for both weapons but applies only the higher result.

### Weapon Durability
On an attack roll of a natural 1, a weapon strikes awkwardly or is fired imprudently and may become damaged, waste ammunition, or become mystically misaligned.

Melee weapons suffer a -1 penalty to damage for every strike they have received. If this penalty would reduce a weapon's total damage roll to 0 or less, the weapon breaks and cannot be used until it is repaired. All melee weapon strikes may be removed from a weapon with an hour's work and access to tools as simple as a whetstone, file, or hammer.
	
Ranged weapons immediately roll their ammo usage die when they receive a strike in addition to the end of the combat in which the weapon was fired.

Magic fighting techniques **gain** an additional damage die of their existing die size when they receive a strike. If any two or more damage dice roll matching numbers, the technique's power exceeds the character's control and immediately deals the total damage rolled to the attacker in addition to the target. All magic fighting technique strikes may be removed with an hour of uninterrupted meditation.
- Note to self: Write a method for warlocks to deliberately overcharge their power to start out with higher dicepools.

## Armor and Shields

Armor:
	Armor provides damage resistance but restricts movement. If you want to avoid the touch of a blade, stay light and move quickly. For those lacking grace, endurance requires steel. Wearing heavy armor imparts a maximum amount of Grace that may be added to the wearer's AC.

	Armor		Slots	Damage Reduction	Maximum Grace Applied to AC
	Unarmored	0	0			No Maximum
	Leather		2	2			4
	Chain 		3	3			3
	Plate		4	4			2

### Armor Durability
Absorbing blows will eventually destroy armor unless it is skillfully maintained. When any die rolled for damage shows the highest value possible on that individual die, armor worn by the target of that damage receives a strike. If a damage roll uses multiple dice, each die showing the highest value possible inflicts a strike. When a suit of armor has a number of strikes equal to the damage reduction it provides, the armor has been destroyed and provides no defensive benefit while it is worn. Destroyed armor may be repaired by paying half the price of the armor in civilization, which removes all strikes from the armor.

Outside of civilization, strikes may be removed from a suit of armor with an hour of work, access to an armor repair kit, and an appropriate skill check; on a total success, one strike is removed from the armor and the kit's usage die is rolled once. On a partial success, one strike is removed from the armor and the kit's usage die is rolled twice. On a failure, no strikes are removed from the armor and the kit's usage die is rolled once, as some materials are wasted.

### Damage Reduction
Grit and Armor both provide points of damage reduction. Reduce all incoming sources of damage by an amount equal to a character's damage reduction. Beware--some attacks may reduce or entirely ignore a character's damage reduction. No matter how much damage reduction a character has, a successful attack always inflicts at least 1 damage.

### Shields
Shields take up between 1 and 3 inventory slots. A shield provides +1 AC per inventory slot it occupies. 

A wielder may use a shield to absorb the brunt of any visible source of damage; when used in this way, the damage is halved before applying the wielder's damage reduction. A shield may absorb a number of strikes equal to the number of inventory slots it occupies before it is destroyed.

3-slot shields are large enough to be used as cover; if a 3-slot shield's wielder does not move during their turn, they may hide their entire body behind the shield. The shield's wielder gains an additional +2 AC against ranged attacks until the start of their next turn.

A shield may be used as a weapon that deals bludgeoning, piercing, or slashing damage as selected at the time of purchase or creation). No weapon modifications may be applied to a shield. A wielder does not gain the shield's bonus to AC until the start of the wielder's next turn after the one in which they make an attack using the shield.


---

	Average Damage by Might/Grace and Weapon Damage Die:
	Stat	1d4	1d6	1d8	1d10	2d6
	0	2.5	3.5	4.5	5.5	7
	1	3.5	4.5	5.5	6.5	8
	2	4.5	5.5	6.5	7.5	9
	3	5.5	6.5	7.5	8.5	10
	4	6.5	7.5	8.5	9.5	11
	5	7.5	8.5	9.5	10.5	12


	Grace 	Grit 	Armor Worn 	AC 	Damage Reduction
	0		0		Unarmored	10	Grit + 0 = 0
					Leather		10	Grit + 2 = 2
					Chain		10	Grit + 3 = 3
					Plate		10	Grit + 4 = 4
			
			1		Unarmored	10	Grit + 0 = 1
					Leather		10	Grit + 2 = 3
					Chain		10	Grit + 3 = 4
					Plate		10	Grit + 4 = 5
			
			2		Unarmored	10	Grit + 0 = 2
					Leather		10	Grit + 2 = 4
					Chain		10	Grit + 3 = 5
					Plate		10	Grit + 4 = 6
			
			3		Unarmored	10	Grit + 0 = 3
					Leather		10	Grit + 2 = 5
					Chain		10	Grit + 3 = 6
					Plate		10	Grit + 4 = 7
			
			4		Unarmored	10	Grit + 0 = 4
					Leather		10	Grit + 2 = 6
					Chain		10	Grit + 3 = 7
					Plate		10	Grit + 4 = 8
			
			5		Unarmored	10	Grit + 0 = 5
					Leather		10	Grit + 2 = 7
					Chain		10	Grit + 3 = 8
					Plate		10	Grit + 4 = 9

	Grace 	Grit 	Armor Worn 	AC 	Damage Reduction
	1		0		Unarmored	10	Grit + 0 = 0
					Leather		11	Grit + 2 = 2
					Chain		11	Grit + 3 = 3
					Plate		11	Grit + 4 = 4
			
			1		Unarmored	10	Grit + 0 = 1
					Leather		11	Grit + 2 = 3
					Chain		11	Grit + 3 = 4
					Plate		11	Grit + 4 = 5
			
			2		Unarmored	10	Grit + 0 = 2
					Leather		11	Grit + 2 = 4
					Chain		11	Grit + 3 = 5
					Plate		11	Grit + 4 = 6
			
			3		Unarmored	10	Grit + 0 = 3
					Leather		11	Grit + 2 = 5
					Chain		11	Grit + 3 = 6
					Plate		11	Grit + 4 = 7
			
			4		Unarmored	10	Grit + 0 = 4
					Leather		11	Grit + 2 = 6
					Chain		11	Grit + 3 = 7
					Plate		11	Grit + 4 = 8
			
			5		Unarmored	10	Grit + 0 = 5
					Leather		11	Grit + 2 = 7
					Chain		11	Grit + 3 = 8
					Plate		11	Grit + 4 = 9

	Grace 	Grit 	Armor Worn 	AC 	Damage Reduction
	2		0		Unarmored	12	Grit + 0 = 0
					Leather		12	Grit + 2 = 2
					Chain		12	Grit + 3 = 3
					Plate		12	Grit + 4 = 4
			
			1		Unarmored	12	Grit + 0 = 1
					Leather		12	Grit + 2 = 3
					Chain		12	Grit + 3 = 4
					Plate		12	Grit + 4 = 5
			
			2		Unarmored	12	Grit + 0 = 2
					Leather		12	Grit + 2 = 4
					Chain		12	Grit + 3 = 5
					Plate		12	Grit + 4 = 6
			
			3		Unarmored	12	Grit + 0 = 3
					Leather		12	Grit + 2 = 5
					Chain		12	Grit + 3 = 6
					Plate		12	Grit + 4 = 7
			
			4		Unarmored	12	Grit + 0 = 4
					Leather		12	Grit + 2 = 6
					Chain		12	Grit + 3 = 7
					Plate		12	Grit + 4 = 8
			
			5		Unarmored	12	Grit + 0 = 5
					Leather		12	Grit + 2 = 7
					Chain		12	Grit + 3 = 8
					Plate		12	Grit + 4 = 9

	Grace 	Grit 	Armor Worn 	AC 	Damage Reduction
	3		0		Unarmored	13	Grit + 0 = 0
					Leather		13	Grit + 2 = 2
					Chain		13	Grit + 3 = 3
					Plate		12	Grit + 4 = 4
			
			1		Unarmored	13	Grit + 0 = 1
					Leather		13	Grit + 2 = 3
					Chain		13	Grit + 3 = 4
					Plate		12	Grit + 4 = 5
			
			2		Unarmored	13	Grit + 0 = 2
					Leather		13	Grit + 2 = 4
					Chain		13	Grit + 3 = 5
					Plate		12	Grit + 4 = 6
			
			3		Unarmored	13	Grit + 0 = 3
					Leather		13	Grit + 2 = 5
					Chain		13	Grit + 3 = 6
					Plate		12	Grit + 4 = 7
			
			4		Unarmored	13	Grit + 0 = 4
					Leather		13	Grit + 2 = 6
					Chain		13	Grit + 3 = 7
					Plate		12	Grit + 4 = 8
			
			5		Unarmored	13	Grit + 0 = 5
					Leather		13	Grit + 2 = 7
					Chain		13	Grit + 3 = 8
					Plate		12	Grit + 4 = 9

	Grace 	Grit 	Armor Worn 	AC 	Damage Reduction
	4		0		Unarmored	14	Grit + 0 = 0
					Leather		14	Grit + 2 = 2
					Chain		13	Grit + 3 = 3
					Plate		12	Grit + 4 = 4
			
			1		Unarmored	14	Grit + 0 = 1
					Leather		14	Grit + 2 = 3
					Chain		13	Grit + 3 = 4
					Plate		12	Grit + 4 = 5
			
			2		Unarmored	14	Grit + 0 = 2
					Leather		14	Grit + 2 = 4
					Chain		13	Grit + 3 = 5
					Plate		12	Grit + 4 = 6
			
			3		Unarmored	14	Grit + 0 = 3
					Leather		14	Grit + 2 = 5
					Chain		13	Grit + 3 = 6
					Plate		12	Grit + 4 = 7
			
			4		Unarmored	14	Grit + 0 = 4
					Leather		14	Grit + 2 = 6
					Chain		13	Grit + 3 = 7
					Plate		12	Grit + 4 = 8
			
			5		Unarmored	14	Grit + 0 = 5
					Leather		14	Grit + 2 = 7
					Chain		13	Grit + 3 = 8
					Plate		12	Grit + 4 = 9

	Grace 	Grit 	Armor Worn 	AC 	Damage Reduction
	5		0		Unarmored	15	Grit + 0 = 0
					Leather		14	Grit + 2 = 2
					Chain		13	Grit + 3 = 3
					Plate		12	Grit + 4 = 4
			
			1		Unarmored	15	Grit + 0 = 1
					Leather		14	Grit + 2 = 3
					Chain		13	Grit + 3 = 4
					Plate		12	Grit + 4 = 5
			
			2		Unarmored	15	Grit + 0 = 2
					Leather		14	Grit + 2 = 4
					Chain		13	Grit + 3 = 5
					Plate		12	Grit + 4 = 6
			
			3		Unarmored	15	Grit + 0 = 3
					Leather		14	Grit + 2 = 5
					Chain		13	Grit + 3 = 6
					Plate		12	Grit + 4 = 7
			
			4		Unarmored	15	Grit + 0 = 4
					Leather		14	Grit + 2 = 6
					Chain		13	Grit + 3 = 7
					Plate		12	Grit + 4 = 8
			
			5		Unarmored	15	Grit + 0 = 5
					Leather		14	Grit + 2 = 7
					Chain		13	Grit + 3 = 8
					Plate		12	Grit + 4 = 9