# First Thoughts

So Balthazar the level 3 mercenary just got stabbed in our last example of gameplay and is about to strike back at those two assassins he's facing. B's got a d10 physical die.

B declares he's hacking at one of the assassins. Balthazar rolls his d10 and gets a 4. He adds his MIGHT of 3 (he's quite brawny) and gets a total of 4 + 3 = 7. He's now got 7 momentum to spend.

There are a number of things you can spend it on, but "Attack" costs 4 momentum. The assassin's defense is 2, which means attacking it increases the momentum cost by 2 to 4 + 2 = 6. He immediately spends 6 momentum, dealing a hit to one of the two assassins. It was that guy's first day on the job, so he sucks and is obliterated in a single hit. B's turn ends. He's got 1 momentum unspent, but he gets to keep up to his level in momentum at the end of his turn, so that that 1 point of momentum stays with him.

The second, more dangerous assassin goes again but misses because I already wrote out a defense example and that's not what I want to talk about right now.

Balthazar's turn comes up again. He wants to strike at this second assassin too, so he rolls his d10 + 3 and gets a total of 7. His held momentum of 1 plus his fresh 7 totals to 8. Balthazar spends all 8 of it to strike the second assassin twice, obliterating it. Combat ends.

~~~
Additional thoughts: 

- Rolling the max face value on your attack die should immediately give you a bunch of momentum to immediately spend.

- Maybe dump all unspent momentum as soon as you roll a 1 on your attack die?

- As-written, this lets you build up momentum by smacking the shit out of weaker enemies before DUMPING on tougher dudes. This matches the idea of momentum, but you could also theoretically use it to model trading blows with a tougher dude before landing one (or a series) of serious blows.

- Additional options for spending momentum are going to be the crux of this combat system; movement, defense, class abilities and equipment that modify the accrual and spending of momentum, etc.

- Modeling slow + heavy + dangerous weapons versus fast/light weapons can be done by modifying the number of dice rolled to gain momentum, or lowering the cost of attacking
- Could also model things like "roll your attack die with advantage" for generating momentum

- Things that exhaust a character can remove existing momentum or apply a penalty to momentum generation.

- Instead of enemy defense applying to the initial die roll, it could apply to AP cost for attacking them. Ex. Baseline strike costs 4, but that assassin with 2 defense requires 6 momentum to actually strike

- Consider: Start players with some amount of Momentum so they aren't defenseless until their turn starts. 
- Or don't? You don't get Momentum until you react!

- Order of operations gets weird re: what you do to generate momentum. What might work out better is if the stat added to the momentum roll is based on what you do first in a turn. Consider this example: 
- "Attack" costs 4. "Move" costs 3. "Interact" costs 2. 
- Balthazar is very strong (Might 3) but only slightly more agile than normal (Grace 1). 
- Balthazar's turn starts and there's a goblin beside him.
- Turn Possibility #1: Balthazar attacks the goblin beside him, rolling + Might (because he's attacking as the first thing he does on his turn). 1d10+3 = 9; he spends 4 to attack. With his remaining 5, he spends 3 momentum to Moves. When he arrives where he wants to go, he has 2 momentum left, which he spends to, I dunno, pull a level or close a door.
- Turn Possibility #2: Balthazar decides moving is more important than attacking, so he darts away, rolling 1d10 + Grace (because moving is the first thing he does on his turn). 1d10+1 = 4. Balthazar spends 3 to Move, and arrives at his destination with 1 momentum left--not enough to pull that lever or close that door.

~~~
WHAT CAN I SPEND MOMENTUM TO DO???
- Attack
- Move
- Cast a spell (non-damaging effect)
- Defend???
- Special Abilities by Class

# Second Thoughts

Defense modes?

~ ~ ~ ~ ~ ~ ~
CONCLUSIONS:
- Your defense mode roll determines if you're struck in the first place or not.
- Armor is abstract harm reduction (NOT contact reduction) and adds additional hits. Light 1, Medium 2, Heavy 4
- Armor bonus hits are a penalty to your Dodge roll.
- Every time you're struck while wearing armor, roll the armor's Usage Die. Light UD4, Medium UD6, Heavy UD8. Destroyed at 0 uses.
- Eventually you're just wearing useless scraps. You can discard it or attempt to repair it later.
- If you're adding a stat to your defense rolls (Parry/Dodge/Block), make sure the negative outcomes happens on "a natural 1 OR a total of 1 or lower"

~ ~ ~ ~ ~ ~ ~

Harm = Severity (number of HD rolls) + Skill (modifier applied to HD rolled).
Severe hits force more rolls of the target's HD. A knife stab is one roll; a giant's axe is three or four rolls.
Attacker skill applies a penalty to each die rolled. An untrained thug is -0; a vicious goblin is -1; a master assassin is -3.

Damage is measured in hits, not HP.

When attacked, pick and roll using defense mode: PARRY, DODGE, or BLOCK.
If struck, roll: 

Parry - High risk, high reward. Steel parries steel; magic parries magic; no overlap.
Critical Failure: Critically struck by attack.
Failure: Struck by attack. 
Success: Deflect incoming attack. No damage.
Critical Success: Deflect incoming attack and immediately riposte.

Dodge - Moderate risk, moderate reward. Steel and magic can both be dodged.
Critical Failure: Struck by attack and forced into bad position.
Failure: Partially avoid attack. Reduced damage.
Success: Entirely avoid attack. No damage.
Critical Success: Entirely avoid attack and may disengage if desired.

Block - Moderate risk, moderate reward. Requires shield. 
Critical Failure: --
Failure: Struck by attack.
Success: Block attack. Immediately roll usage die for shield.
Critical Success: --

WHEN HIT BY AN ATTACK: Reduce damage by flat armor value + GRIT

Best:	No damage, no contact
Good:	No damage, contact
Okay:	Reduced damage, contact
Bad:	Full damage, contact
Worst:	Enhanced damage, contact - 

# Third Thoughts

Combat Flow ideas

USE EXISTING MECHANICS TO DEMONSTRATE DIFFERENCES. (Add depth, avoid complexity; beware over-linkage)

"Momentum"

fully engage: roll off for momentum, higher result inflicts difference to lower result as momentum cost

- test foe for opening
- initial attack
- press advantage
- reversal
- disengage/reposition

Modes of Attack?
- Might/Grace/Lore?
- Force/Finesse?
- strike/feint/defend/reposition
- strike + wager momentum
- versus defend: no hit, attacker momentum wagered subtracted from foe's momentum (if foe momentum <= 0, smash through defense and inflict hit)
- versus feint: ?
- versus strike: higher wager inflicts hit; lower wager momentum lost
- versus reposition: 
- feint + wager momentum
- versus defend: no hit, immediately add foe's wagered defend momentum to your own
- versus feint: ?
- versus strike: ?
- versus reposition: 
- defend + wager momentum
- versus defend: ?
- versus feint: ?
- versus strike: ?
- versus reposition: 

Stats required:
Attack die + mod
Hits before death
Momentum sustained per round
Armor + Weapon

~ ~ ~ ~

Gawain: 1d10+2, 3/3 hits
Armor: Chain (UD6, -2/round)
Weapon: 2H Axe (+2 strike)
AI: 1 Strike (wager half), 2 Strike (wager all), 3 Feint (half), 4 Defend (half), 5 Reposition (half?), 6 Nothing

~ ~ ~ ~

Lancelot: 1d10+2, 3/3 hits
Armor: Chain (UD6, -2/round)
Weapon: 1H Sword + Shield (+2 Defend)
AI: 1 Strike (half), 2 Feint (half), 3 Defend (wager half), 4 Defend (wager all), 5 Reposition (, 6 Nothing

~ ~ ~ ~

Combat #1 Begins.
Lethal intent: Matched - to first blood (successful hit)

Exchange #1:
Duel initiative: Gawain 4, Lancelot 10. Current momentum: Gawain 4, Lancelot 10.
Gawain Strikes (wager 2) for 1d10+4; Lancelot Strikes (wager 10) for 1d10+12.
Gawain 12, Lancelot 21. Higher wager + roll inflicts hit; lower wager momentum lost. Tie = CLINCH
Lancelot strikes Gawain! Gawain rolls armor: 4 (no hit).
In the exchange, Gawain loses 2 momentum. Lancelot loses 10 momentum. Current momentum: Gawain 2, Lancelot 0.
End of Round: Chain armor costs Gawain 2 momentum. Chain armor costs Lancelot 2 momentum. Current momentum: Gawain 0, Lancelot -2.

Exchange #2:
Duel initiative: Gawain 11, Lancelot 4. Current momentum: Gawain 11, Lancelot 2.
Gawain Feints (wager 5) for 1d10+7; Lancelot Defends (2) for 1d10+4.
Gawain 10, Lancelot 7. Immediately add foe's wagered defend momentum + roll to player.
Gawain successfully feints at Lancelot! 
In the exchange, Gawain gains 7 momentum and Lancelot loses 2 momentum. Current momentum: Gawain 13, Lancelot 0.
End of Round: Chain armor costs Gawain 2 momentum. Chain armor costs Lancelot 2 momentum. Current momentum: Gawain 11, Lancelot -2.

Exchange #3:
Duel Initiative: Gawain 12, Lancelot 11. Current momentum: Gawain 23, Lancelot 11.
Gawain does Nothing. Lancelot does Nothing. Player and foe stare at each other. Player and Foe roll duel initiative again and add respective totals to momentum.
Duel Initiative: Gawain 12, Lancelot 7. Current momentum: Gawain 35, Lancelot 18.
End of Round: Chain armor costs Gawain 2 momentum. Chain armor costs Lancelot 2 momentum. Current momentum: Gawain 33, Lancelot 16.

Exchange #4:
Duel Initiative: Gawain 12, Lancelot 11. Current momentum: Gawain 45, Lancelot 27.
Gawain Strikes (wager 35) for 1d10+39; Lancelot Defends for 1d10+29.
Gawain 41, Lancelot 39. Player momentum wager + roll subtracted from foe's momentum wager + roll. If foe's wagered momentum + roll <= 0, player defeats defense and inflicts a hit. If foe's wager + roll remains positive, subtract positive value from player's momentum.
Gawain strikes Lancelot! Lancelot rolls armor: 1! The blow strikes true! Lancelot's armor die drops to UD4.

GAWAIN DRAWS FIRST BLOOD! GAWAIN WINS!

~ ~ ~ ~ ~

Questions raised by this combat: 
- Can armor reduce your momentum below 0? (YES)
- Do you need to wager momentum on a reposition? What happens if it's not opposed (YES; WAGERED MOMENTUM IS LOST BUT SUCCESS ZEROES IT ANYWAY SO WAGER IT ALL)
- Easy way to remove non-full reposition wager as trap option?
- When you wager momentum, do you get it back + winnings on success? (NO; ELSE IT WOULD DEATH SPIRAL WITHOUT ADDITIONAL RESETS)
- Do I need to tone down momentum drain from armor? Exchange #2 had a net-zero effect on momentum. (KEEP PLAYTESTING)