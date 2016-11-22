---
title: Combat
---

* TOC
{:toc}

To defeat your opponents in combat, you must first build **Initiative**, which is a number that represents your combat momentum, with **withering attacks** against your opponents. Withering attacks represent testing blows, feints, glancing hits, and other attacks that push an opponent off-balance but don't cause them more than superficial damage. Withering attacks reduce your opponents' Initiative while increasing your own.

Against opponents that you dramatically outclass, you may not need to use a withering attack at all. Against skilled opponents, though, just leaping right in for the kill can get you killed yourself... which is why you'll want to wait for just the right moments in the fight to spend your Initiative on **decisive attacks**. With a decisive attack, you can deal substantial damage, or even incapacitate or kill an opponent in one blow.

## The Flow of Combat

Combat is split into **rounds**. Each round is composed of **ticks**, which are abstract, very small measures of time, count from highest to lowest, and can start at any number. During each round, you take your turn on the tick matching your Initiative, going from highest to lowest. If multiple characters act on the same tick, they go simultaneously. Once everyone in the combat has taken their turn, the next round starts.

Your starting Initiative in combat is the result of a **Join Battle** roll. This is a (Wits + Awareness + 3s) opposed roll. If you join combat that's already started, you roll Join Battle as non-opposed roll to determine your starting Initiative,[^winning-initiative][^join-battle-plus-three] and then take your first turn the next time the tick matching your Initiative comes up.

[^winning-initiative]: This isn't an opposed roll, but you're considered to "win" for the purpose of effects that trigger from that if you have a higher result than the current Initiative of any opponent in the combat.

[^join-battle-plus-three]: In the original text, it's unclear if someone joining an existing combat gets the +3s bonus. As a best-guess interpretation that bonus is included here.

Your Initiative can rise or fall to any number. If an effect increases or lowers your Initiative, it's written Xi, where X is the amount. Some effects will **reset** your Initiative to your **base Initiative**, which for most characters is 3, but for some characters may be higher or lower.

If you have low Initiative and haven't acted yet, and you increase your Initiative to greater than that of other characters who have already acted, you take your turn on the next tick. No matter how your Initiative changes, you only take your turn once in a given a round.

If you would take your turn but want to wait, you can delay your action to a later tick. This costs 2i, but you can take your action on any tick later in the round than your original Initiative, including on the same tick as another character. This can be useful to set up [Clash attacks](#clashes) or for coordinating a fight with your allies.

## Crash

If your Initiative falls to 0 or lower, you're in **Crash** as long as you have a Initiative that's 0 or lower. If you Crash yourself, such as by using actions or Charms that cost Initiative, you lose an additional 5i.

While you're in Crash, withering attacks can continue to lower your Initiative, and you're subject to the following effects:

- You have [Hardness](#hardness) 0, except for Hardness that specifically works while in Crash.
- You can't make decisive attacks.
- You can't use effects with the Perilous keyword.

If you end three consecutive turns in Crash, your Initiative resets to your base Initiative at the beginning of your next turn.

If you Crash another character (by any means), you gain a +5i **Break** bonus. You can't get the Break bonus by Crashing a character on the round that character recovered from Crash or on the round after that.

If you Crash yourself, whichever character is most responsible for causing that self-Crash (at the ST's discretion) gets the Break bonus.

If a character Crashes you, and while you're in that Crash you Crash them, you **Shift**. Your Initiative resets to your base Initiative if it's lower than that, and you roll Join Battle as if you were joining combat and add the result to your Initiative. Then your turn starts over, and you can use a full set of actions again during the same turn. During the rest of that turn, if you attack, you can only attack the character you put in Crash in order to achieve Shift.

If you're in Crash because of your own actions, you can't Shift.

## Positioning and Movement

A battlefield is divided up into **zones**.[^new-zones] These don't need to be precisely measured areas (and usually shouldn't be), but should instead be a way to quickly divide up the local terrain. Generally, the denser the terrain and the harder it is to be mobile, and the busier it is, the smaller the zones should be. For example, in a crowded city, each city block might be a zone, while in more open terrain a huge open field could be a single zone. The **range** from one character to another depends on the zones that they're in.

[^new-zones]: The original text only uses ranges and range bands, not zones. Zones are used here to increase clarity of play for most readers. The mechanical end result is effectively the same as the original text's use of range bands, but slightly more formalized.

Characters who are within arms' reach of each other or engaged in melee combat are at **close range**. Characters need to be at close range to target each other with close combat weapons. Different groups of characters can be at close range with each other in the same zone, treating their own group as close range and the rest of the zone as short range.

Characters in the same zone are at **short range** from each other. They aren't in reach of each other, but can easily go to close range from there, and have no problems attacking each other with ranged combat weapons.

Characters in adjacent zones are at **medium range** from each other. Talking to each other requires shouting, and ranged combat attacks require using the [Aim](#aim) action first.

Characters two zones apart are at **long range** from each other. At this range, direct communication is impossible except by means such as semaphore flags, and characters have a hard time telling the details of each others' actions. Only long-ranged weapons can be used to attack at this range, and they require aiming first.

Characters at least three zones apart are at **extreme range** extreme from each other. Combat and direct communication between characters at extreme range is impossible, barring specialized extremely-long-range weapons.

To cross between zones, you **cover ground**.[^new-covering-ground] When an action tells you to "cover ground X", you cross that many zones. You're still limited by what makes sense for the terrain. For example, if you're on one side of a tremendous crevice several zones across, you'll probably have to go around to cross it.

[^new-covering-ground]: "Covering ground" is used here as a mechanical term to give more clarity than the original text's use of "movement" and "movement actions". If an effect tells you to move one or more range bands, consider that to be covering ground.

Close range is a special case: you cover ground 1 to enter or exit close range with another characters or characters, but if any opponents don't want you to exit close range, you have to succeed at a [Disengage](#disengage) action. You have to exit close range before you can cover ground to an another zone.

Except for the special case of close range, you can move around inside a zone without needing to cover ground or use a Movement action. For example, if you're in a zone that contains a building, you can leap up to the roof to Rush an opponent there without needing to use another action to get there.

Areas like thick forest, collapsed buildings, or pens filled with angry yeddim are considered difficult terrain. A zone of difficult terrain counts as two zones for the purposes of covering ground with the [Move](#move) action (but not other actions). You stay inside or outside the zone until you've covered both.

## Stealth in Combat

If you're hidden from an opponent when combat starts, you're **concealed** from them. This lets you make a surprise attack against them (see [Attack](#attack)).

{:#concealment-roll}
Some actions may call for a **concealment roll**. This is a (Dexterity + Stealth) opposed roll against the (Wits + Awareness) of all opponents. Your roll gets a -3 penalty if you make it in combat (but not if you've hidden ahead of time). If your opponents aren't allies of each other or are bad at working together, use the same roll result but treat like a separate opposed roll against each separate group or opponent, and keep track of concealment against each of them separately.[^new-separate-concealment]

[^new-separate-concealment]: The rule for non-allied opponents doesn't exist in the original text, but is added here as a common-sense clarification for these kinds of situations.

If you're concealed against opponents and cover ground or use a Movement action, you have to make a concealment roll. If you win, you remain concealed; if you lose, you're revealed to those opponents.

## Combat Actions

Each turn, you can use one **Simple** action and any number of **Reflexive** actions.

You can **flurry** to take a second Simple action in a round, but it has to be a different action from the first, and both actions have to have the Flurry keyword. When you flurry, you get -3 to any rolls used by either Simple action, and you get -1 to your Defense until your next turn. Some actions can't be used on a turn when you flurry.

If an action gives you a Defense modifier, then you get that bonus or penalty to Defense from when you declare the action until the start of your next turn.

Some actions have the **Movement** keyword. You can only use one Movement action in a turn, unless another rule says otherwise.

If multiple characters act on the same tick, Simple actions are used in order from the highest Join Battle rating to the lowest, with (Dexterity + Athletics) as a tiebreaker.[^new-tick-resolution] Reflexive actions may be used at any time in the order, but can't interrupt other actions. (For example, a Move used in response to an Attack would happen after the attack, not before.) If one character attacks another under the right conditions for a [Clash](#clashes), the second character may immediately use an Attack against the first character even if it's not their place in the order yet.

[^new-tick-resolution]: This method of resolution for simultaneous actions and Clashes don't exist in the original text. It's been added here to speed play and encourage the use of Clash attacks by removing the inevitable arguments about who goes first on a given tick.

The list of combat actions is:[^new-collected-actions]

[^new-collected-actions]: In the original text, many of these actions or their effects are presented in an informal or fragmented way. All combat actions have been gathered together here for clarity.

### Aim

**Defense** ---  
**Action** Simple; **Duration** Instant  
**Requirement** You can't use this action on the same turn you cover ground or use a Movement action, and vice versa, unless another rule says otherwise.

Choose a target within the maximum range of a readied weapon. Depending on your range from the target:

* *short range or closer:* If you attack the target on your next turn, you get +3 on the attack roll.
* *medium or longer range:* You can attack the target on your next turn. If you spend two consecutive turns using the Aim action targeting them and then attack them on the turn after that, you get +3 on the attack roll.

If you Aim and the target covers ground out of your weapon's range or gets behind full cover before your next turn, the Aim action is wasted.

If you're casting a spell, using an effect from an Ability or martial art that isn't typically used to make ranged attacks, or benefiting from an immediate ranged attack generated by some effect, you don't need to Aim to attack at medium or longer range.

### Attack

**Defense** ---  
**Action** Simple; **Duration** Instant  
**Keywords** Flurry

You use a readied weapon to make an attack against a target. See [Ready Weapon](#ready-weapon) and [Resolving Attacks](#resolving-attacks).

### Defend Other

**Defense** ---  
**Action** Simple; **Duration** 1 round  
**Keywords** Flurry  
**Requirement** You have an ally at close range.

Choose an ally within close range. You apply your Parry against all attacks targeting that ally, called your ward.

If one of those attacks succeeds against your Parry, the attacker chooses to apply the attack to you or to your ward. If they apply it to your ward, their attack roll result becomes just their threshold successes, and they still have to succeed against your ward's Defense. If the attack is a decisive attack, the attacker also loses (your Defense ÷ 2, rounded down) from the damage roll.

### Disengage

**Defense** ---  
**Action** Simple; **Duration** Instant  
**Keywords** Flurry, Movement  
**Requirement** You're at close range with any opponents.

When you use this action, you lose 2i.

Make a (Dexterity + Dodge) opposed roll against the (Dexterity + Athletics) of any opponents at close range who want to stop you from exiting close range. You get -3 if you're in difficult terrain.

If you win, cover ground 1 to exit close range. The first time any opponent you rolled against covers ground towards you on their next turn, you cover ground 1 away from them as a Reflexive action.

If you lose, you don't get to exit close range.

### Establish Surprise

**Defense** ---  
**Action** Simple; **Duration** ---  
**Requirement** You're somewhere it's reasonable to break line of sight and hide.

Make a [concealment roll](#concealment-roll) against all opponents who are aware of your presence. You're concealed against any opponents you win against.

### Full Defense

**Cost** 1i; **Defense** +2  
**Action** Simple; **Duration** Instant  
**Keywords** Flurry, Perilous  
**Requirement** You aren't in Crash.

This action doesn't do anything by itself, but it has a positive Defense modifier.

You can only flurry this action with social influence actions.

### Go to Ground

**Defense** ---  
**Action** Simple; **Duration** Instant  
**Keywords** Movement  
**Requirement** You're concealed against all opponents.

To complete Go to Ground, you have to use this action three turns in a row.

Each turn, make a [concealment roll](#concealment-roll). On the second turn, the penalty increases to -4, and on the third turn it increases to -5. You have to win all three rolls against all opponents.

If you complete Go to Ground, you're completely hidden and can't be found until well after the combat is over. Willingly rejoining the same fight sets your Initiative to -10.

### Move

**Defense** ---  
**Action** Reflexive; **Duration** Instant  
**Keywords** Movement  
**Requirement** You're not at close range with any opponents, and it is your turn.

You cover ground 1.

### Ready Weapon

**Defense** -1  
**Action** Simple; **Duration** Instant  
**Keywords** Flurry

You ready or unready a weapon, or both. You can treat a set of small, identical weapons (such as throwing knives) like one weapon for the purpose of readying. How many weapons you can have ready is up to your ST,[^new-readied-weapons] but as a guideline you can usually have up to two large weapons ready (such as a sword in each hand) and any number of small weapons ready (such as a set of throwing knives strapped to your hip). Any weapon ready in your off-hand gets a -1 penalty to attacks.[^off-hand-penalty]

[^new-readied-weapons]: The original text doesn't give any guidelines for readying multiple weapons. Common-sense guidelines for multiple weapons have been added here.

[^off-hand-penalty]: See Ambidextrous on page 158 of *Exalted 3*.

If you expect combat---or start it yourself---you can start combat with any weapons of your choice ready to attack with. If you're attacked without expecting it, you usually don't start combat with any weapons ready.[^paranoid]

[^paranoid]: If you're the sort of person who's so paranoid that you keep a weapon ready at all times, you should make sure the ST knows that ahead of time. After all, if you always walk around with a sword or a spear in hand, people might start suspecting that you want to attack them.

Your natural weapons, like fists or claws, are always ready.

### Rise From Prone

**Defense** ---  
**Action** Simple; **Duration** Instant  
**Keywords** Flurry, Movement  
**Requirement** You're prone.

You get up from being [prone](#prone).

If an opponent is at close range, you have to roll (Dexterity + Dodge) against difficulty 2. If you fail, you don't get up.

### Rush

**Defense** ---  
**Action** Simple; **Duration** until target's next movement  
**Keywords** Flurry, Movement

Make a (Dexterity + Athletics) opposed roll against a target at short range. You get -3 on the roll if you're in difficult terrain.

If you win, the next time that target covers ground, you immediately take a Reflexive action to cover ground 1 to follow them. Unless it's physically impossible to follow an opponent, the Reflexive action isn't optional.

Using this action while concealed ends your concealment.

If you've already used a [Move](#move) action this turn, you can still use Rush as though you hadn't used a Movement action this turn.

### Take Cover

**Defense** ---  
**Action** Simple; **Duration** Instant  
**Keywords** Flurry, Movement

Roll (Dexterity + Dodge) at a difficulty set by the ST depending on how much cover is available. If you succeed, you benefit from light, heavy, or total cover as appropriate.

* *light cover:* Things that shield about half your body, like standing behind an overturned table or a full-sized oxcart. +1 Defense.
* *heavy cover:* Things that shield most of your body, like firing arrows from a small window in a stone wall or standing behind the bulk of an elephant. +2 Defense.
* *total cover:* Things that completely shield you, like standing behind a solid wall. You can't be targeted by attacks unless they break through or go around the cover.

At close range, an opponent attacking you while you're in cover also gets the benefits of that cover on Defense against you. At longer range, opponents can usually move one or more zones to circumvent that cover by attacking from a different direction.

Cover is limited as makes sense given the actual terrain. For example, if you're in heavy cover by standing behind a shoulder-height stone wall, an opponent at close range can jump over the wall to attack you from the same side.

### Withdraw

**Defense** ---  
**Action** Simple; **Duration** Instant  
**Keywords** Flurry, Movement  
**Requirement** You're at medium or greater range from all opponents.

You cover ground 1 away from all opponents.

Make a (Dexterity + Athletics) extended roll against difficulty 1, with an interval of one round and a goal of 10. You get -3 on the roll if you're in difficult terrain. Each time you make an individual roll, you lose 10i. If you succeed on the extended roll, you cover ground 1 away from all opponents. If you're already at extreme range from all opponents, you exit the battlefield completely.

### Other Simple Action

**Defense** -1  
**Action** Simple; **Duration** Various  
**Keywords** Flurry

You can do anything not listed that would make sense as a Simple action. This includes anything not given as an action that you could do in a few seconds in the stress of combat.

## Gambits

**Gambits** are a special kind of decisive attack. They use the same combat resolution as decisive attacks except for the differences noted for gambits (see [Resolving Attacks](#resolving-attacks)), and instead of dealing damage have special effects, like disarming or grappling an opponent. These are particularly useful for negating the advantages of powerful or hard-to-hurt opponents, or for ending fights without actually hurting anyone.

Some unique opponents may require the use of special gambits to defeat, like tangling the many heads of a hydra or decapitating otherwise deathless zombies. The ST provides the details of these as needed, but characters might need to research the tactics needed first for things that aren't common knowledge.

### Disarm

**Gambit**; **Difficulty** 3  
**Requirement** The target has a weapon ready.

If you complete the gambit, you disarm the target of one of their readied weapons, and it's thrown up to short range away from them. Anyone in the same zone as it can retrieve it (and if they wish, ready it) with a [Ready Weapon](#ready-weapon) action.

### Distract

**Gambit**; **Difficulty** 3--5 (your choice)  
**Requirement** You have at least one non-Crashed ally on the battlefield.

Choose a target non-Crashed ally and a target opponent. If you complete the gambit, the ally gains Xi, where X is the Initiative that you lost from the gambit. If the ally doesn't attack the opponent on their next turn, they lose Xi at the end of that turn.

A character can only benefit from one Distract gambit at a time.

### Grapple

**Gambit**; **Difficulty** 2

If you complete the gambit, you grab the target. You have control of the grapple for this round.

Make a (Strength + [Brawl or Martial Arts]) opposed roll against the target. You have X **control rounds**, where X is the threshold successes if you win or 0 if you lose. At the start of each of your turns, you lose 1 control round. If you have 0 control rounds at the start of the target's turn, they escape the grapple. If you are Crashed during the grapple, the target escapes the grapple immediately.

Maintaining the grapple is a Simple action with the Movement keyword. You can choose to release the target at any time as a Reflexive action, including during someone else's turn or just before the start of your turn, in which case at the start of your turn you can act normally.

While the grapple is active, you and the target can't flurry and get -2 Defense, and the target can't use Movement actions and gets -1 to attacks (or -3 to two-handed attacks).

Each time you're attacked while the grapple is active (even if the attack isn't completed), and each time you're damaged, you lose 1 control round.

The turn you complete the gambit, and at the start of each turn you have control rounds remaining, you can choose one **maneuver** to use:

* *Restrain/Drag:* This maneuver costs 2 control rounds to use. The target can't take any non-Reflexive actions on their next turn. You can immediately use any Movement action, which you use as a Reflexive action instead of its normal type. If you do, you take the target along with you.

* *Savage:* Choose one: Make an unarmed withering attack against the target, their Defense is 0 against the attack, and the attack roll automatically succeeds; or, make an unarmed decisive attack against the target, and the attack roll automatically succeeds.

* *Throw/Slam:* This works as the savage maneuver, except that you increase the damage pool by (your control rounds or Strength, whichever is lower), or double that increase for a withering attack. After the attack the target is rendered [prone](#prone), and the grapple ends immediately.

### Unhorse

**Gambit**; **Difficulty** 4  
**Requirement** The target is on a mount.

If you complete the gambit, you knock the target off their mount. The target is rendered [prone](#prone) and takes 1bhl damage from the fall.

Most normal mounts will flee in the confusion, but mindless or particularly well-trained mounts will remain in the same zone, ready to be remounted.

## Resolving Attacks

To attack a target with a weapon, you need to have that weapon readied (see [Ready Weapon](#ready-weapon)).

If it's a close combat attack, you can only make the attack at close range. If it's a ranged combat attack, you need to [Aim](#aim) first to attack at medium or longer range, except under certain conditions.

### Attacks From Stealth

If you're concealed against the target, this is a **surprise attack**. The target gets -2 Defense against it. If you don't incapacitate or kill the target with this attack, you're revealed to the target and their allies.

If it's the first round of the combat and you make a surprise attack against a target with lower Initiative with you, then the attack is an **ambush**, and the target has Defense 0 against it.

If you ambush a target, you can **hold at bay** the target instead of resolving the attack normally. If you do, for (your Initiative - target's Initiative) rounds, you have the target held hostage. You get +1 Resolve and Guile and the target gets -2 Resolve and Guile during this time.

If the target tries to escape during those rounds, you may make a decisive ambush attack against the target as a Reflexive action. It gets +5s to the damage roll and treats the target's Hardness as 0.

When those rounds have passed, if you haven't gotten the target to surrender or otherwise cooperate, you and the target both roll Join Battle to see who acts first, with the target getting -2 to the roll. If you win, you can immediately perform an ambush attack against the target.

### Resolution Steps

Each attack has an order of operations used to resolve it. Usually you won't need to keep track of the exact steps, but if you're fighting another magical being, using them helps prevent any confusion about figuring out what happens.[^new-steps]

[^new-steps]: The original text lacks a comprehensive set of steps for resolving an attack. These steps have been assembled based on a best-guess interpretation of the rules as intended.

1. Declare the target of the attack, and choose if it's a withering attack or a decisive attack. When declaring actions during the action phase, pause after this step.

2. Declare and pay for any effects that apply to the attack as a whole or to the attack roll.

3. The target declares and pays for any effects that apply against the attack as a whole or against the attack roll.

4. The target declares whether to apply Parry or Evasion.

5. Your dice pool for the **attack roll** is (Dexterity + attack Ability) against a difficulty of the target's Defense. If it's a withering attack, also add (your weapon's accuracy).

6. Whether the attack roll succeeds or fails:

    a. The target gets a -1 onslaught penalty to Defense until their next turn.[^new-when-onslaught-penalty]

7. If the attack roll fails:

    a. If it's a decisive attack, you lose 2i, or 3i if your Initiative is 11+.

8. If the attack roll succeeds:

    a. Declare and pay for any effects that apply to the damage roll.

    b. The target declares and pays for any effects that apply to the damage roll.

    c. Assemble your **damage roll**. This depends on the attack type.

      * *withering:* The damage roll is (Strength + weapon damage bonus + threshold successes from the attack roll - target's soak), minimum of your minimum damage. After checking the minimum, add any post-soak damage.

      * *decisive:* The damage roll is (your current Initiative). The Double 10s rule doesn't apply. If this isn't a gambit and the target has Hardness equal to or greater than the damage roll, change your damage roll to 0.

    d. Roll the damage roll and apply damage. This depends on the attack type.

      * *withering:* The target loses Xi, where X is the successes from the damage roll. You gain (X + 1)i.

      * *decisive:* The target takes X health levels, where X is the successes from the damage roll. Then, apply any automatic damage from other effects.

      * *gambit:* Instead of applying damage, apply your damage roll against the difficulty of the gambit. If you succeed, you complete the gambit.

    e. If this is a decisive attack, your Initiative resets to your base Initiative. If this is a gambit, instead of resetting your Initiative, you lose (gambit's difficulty + 1)i.

    f. If the target is Crashed by the attack, apply Break or Shift.

9. Whether the attack roll succeeds or fails:

    a. Resolve Counterattack effects declared in step 3.

      1. If a counterattack explicitly resolves at a different time, do so then, but use the same guidelines here.[^new-when-counterattacks]

      2. If a Counterattack includes an attack, fully resolve that attack before continuing the resolution of this attack. Any effects from a Counterattack (such as Initiative changes or wounds) affect you from this step forward. If you're incapacitated by a Counterattack, your attack ends.[^new-counterattack-incapacitation]

[^new-when-onslaught-penalty]: When the onslaught penalty is applied isn't clarified in the original text, but has been noted here as a best guess for attack resolution.

[^new-when-counterattacks]: The original text gives no information on when a counterattack should be resolved. It has been placed here as a best guess.

[^new-counterattack-incapacitation]: What happens with incapacitation by a Counterattack isn't clarified in the original text, but has been noted here as a best guess for attack resolution.

## Clashes

If two characters attack each other on the same tick, it's a **Clash**. Clashes are a direct contest of martial power instead of the usual dance of blow and counterblow.

To resolve a Clash, you use the normal attack resolution, with some modifications. Both characters proceed through the same set of steps simultaneously.

When declaring effects to enhance the attacks in step 2, the characters alternate[^new-clash-alternating] in order from the highest Join Battle rating to the lowest, with (Dexterity + Athletics) as a tiebreaker, with each declaring any effects until neither declares another to activate.

[^new-clash-alternating]: The original text doesn't give any order of application of effects for Clash attacks. This is added here as a reasonably fast and interesting way to apply these effects.

Instead of being used against Defense, the attack rolls are used as opposed rolls.

The winner deals damage as though they succeeded against the loser's Defense, with threshold successes from the opposed roll adding dice to the damage roll if it's a withering attack. The winner gets +3s on the damage roll if they're making a withering attack, or +1s on the damage roll if they're making a decisive attack.

The loser's attack ends, and they get -2 Defense until their next turn. This penalty doesn't stack with itself. They don't get any onslaught penalty from the winner's attack.

### Clashes and Multiple Attacks

Only matching "pairs" of attacks count as Clashes.[^new-clash-pairs]

[^new-clash-pairs]: This rule isn't in the original text, but is added here to aid with resolution of Clashes and multiple attacks.

If you make multiple attacks against a character attacking you once on the same tick, only the first pair of attacks counts as a Clash, and your additional attacks are resolved normally.

If you make multiple attacks against a character also making multiple attacks against you, then each matched pair of attacks is resolved as a Clash, and any additional attacks on either side are resolved as normal attacks.

If a Clash or other effect causes a character to become incapacitated in the middle of making multiple attacks, then any following attacks are canceled and don't happen.

## Defending Against Attacks

You have two main defenses against attacks: Parry and Evasion. Your **Defense** is the higher of whichever of these you can apply against an attack. If something gives a bonus or penalty to Defense, it applies to both Parry and Evasion. All onslaught penalties to your Defense stack.

Your **Parry** represents intercepting and deflecting an attack with a weapon (or with your own body), and you can only use Parry with a close combat weapon. Your Parry rating is ([Dexterity + attack Ability + specialization] ÷ 2 + weapon's Defense bonus). You can't apply your Parry against an attack that's unblockable unless another rule says otherwise.

Your **Evasion** represents completely avoiding an attack. Your Evasion rating is ([Dexterity + Dodge + specialization] ÷ 2 - armor's Defense penalty). You can't apply your Evasion against an attack that's undodgeable unless another rule says otherwise.

### Resisting Attacks

If an attack gets past your Defense, your soak and Hardness can still protect you.

{:#soak}
Your **soak** applies against withering attacks, subtracting from the damage pool. Your soak rating is (Stamina + armor's soak bonus).

{:#hardness}
Your **Hardness** starts at 0, but can be increased by some kinds of armor and by magical effects. Hardness doesn't subtract from damage, but can negate some decisive attacks completely. Hardness from different sources doesn't stack unless the source says otherwise.

### Damage and Conditions

If your Defense, soak, and Harness aren't enough to protect you, an attack can deal damage to you.

{:#prone}
If an effect renders you **prone**, you get -1 to Parry, -2 to evasion, -3 to attack rolls, and you can't use any Movement actions except for [Rise From Prone](#rise-from-prone). You need to [Rise From Prone](#rise-from-prone) to get back up.

## Mounted Combat

Since mounts are faster than people on foot, being on a mount gives a speed bonus to the rolls for some actions. See the table.

| Mount         | Speed |
|:--------------|:-----:|
| Austrech      |  +2   |
| Camel         |  +3   |
| Horse         |  +4   |
| Mammoth       |  +1   |
| Simhata       |  +4   |
| Tyrant lizard |  +2   |
| Yeddim        |  +1   |

When attacking from a mount, you get +1 to attack rolls for withering attacks against non-mounted targets, or +2 for withering attacks against battle groups armed with non-reaching weapons. You get +1 to Defense against close-range non-reaching weapons wielded by non-mounted opponents.

Some mounts give different bonuses instead of these combat bonuses. For example, very light and fast mounts such as riding eagles may give no combat bonuses at all, while extremely large mounts like elephants may protect you completely from non-reaching close-range weapons unless the opponent also climbs on the mount.

Mounts usually don't have their own actions or Initiative. For a mount without its own Initiative, anything that would affect the mount's Initiative (including withering attacks) affects the rider's Initiative instead. For a mount without its own actions, the mount's rider can use his own actions as appropriate to command the mount, including being able to flurry.

## Battle Groups

When there are more than two participants in combat who are allies, mechanically fairly similar, and who aren't individually important to the ST's story, they should be tracked as a **battle group**. A battle group works mechanically like a single character, but represents the coordinated action of multiple combatants.

Battle groups always use withering attacks, and instead of taking Initiative damage or health damage, take all damage to a special **Magnitude Track** that represents the morale and cohesiveness of the group. A battle group's Initiative is only used to keep track of the battle group's place in the turn order, and never increases or decreases.

The **Size** of a battle group represents the number of combatants in it. The Size of a battle group is added as a bonus to that battle group's attack rolls, damage, Magnitude, and soak rating.

| Size | Number of fighters                |
|:----:|:----------------------------------|
|  0   | 1--2                              |
|  1   | 3--12                             |
|  2   | 13--100                           |
|  3   | 101--300                          |
|  4   | 301--1000[^whats-several-hundred] |
|  5   | 1001+                             |

[^whats-several-hundred]: This is an interpretation of the original source's "several hundred combatants".

The **Drill** of a battle group represents how well these combatants work together. The Drill of a battle group can affect command rolls for that battle group and grants a bonus to that battle group's Defense.

| Drill   | Effects                                                                   | Defense | Examples                                                     |
|:--------|:--------------------------------------------------------------------------|:-------:|:-------------------------------------------------------------|
| Poor    | -2 to Order and Rally for Numbers, +1 difficulty for rout and rally rolls |   +0    | Poorly-trained raiders, wild mobs, inexperienced conscripts  |
| Average | ---                                                                       |   +1    | Professional guards, skilled mercenaries, veteran conscripts |
| Elite   | +2 to command rolls                                                       |   +2    | Warrior-monks, imperial special forces                       |

The **Might** of a battle group represents the power and potency of these combatants. The Might of a battle group grants a bonus to that battle group's accuracy, damage, and Defense.

| Might | Accuracy | Damage | Defense | Examples                                          |
|:-----:|:--------:|:------:|:-------:|:--------------------------------------------------|
|   0   |    +0    |   +0   |   +0    | Mortals                                           |
|   1   |    +1    |   +1   |   +1    | Powerful beastfolk, mortals under divine blessing |
|   2   |    +2    |   +2   |   +1    | Lesser spirits like ghosts or first circle demons |
|   3   |    +3    |   +3   |   +2    | Terrestrial Exalted                               |

### Actions

Battle groups take actions as normal, except as noted here.

* Battle groups can cover ground away from opponents two or more points of Size smaller than the group without needing to Disengage.
* Instead of using the Grapple gambit, battle groups use the Engage gambit. This gambit is identical to Grapple, except that instead of rolling damage, the gambit automatically completes. The roll to determine the number of control rounds uses the group's combat Ability rather than Brawl or Martial Arts. The gambit doesn't have the Restrain/Drag and Throw maneuvers, and the Savage maneuver uses the group's standard attack type rather than an unarmed attack.

### Attacks and Defenses

When a battle group attacks, it applies the same attack to all enemies at close range with the battle group (when making a close-ranged attack) or to all characters within close range of a primary target (when making a ranged attack). A battle group can spread out to count as being at close range with more characters, but loses Size bonuses to attacks if the average distance between group members is 10 yards or more.

Battle groups always make withering attacks, but don't gain Initiative from them. If a battle group would deal Initiative damage to a target in Crash, it's instead applied as bashing or lethal health damage, as appropriate for the battle group's weapons. Battle groups don't double each 10 on damage rolls.

Battle groups have a Magnitude equal to the average number of health levels the fighters of the battle group have (usually 7), plus the battle group's Size. When a battle group takes damage from an attack, that damage reduces the battle group's Magnitude. If that attack is a decisive attack, it also deals (damage dice rolled ÷ 4) additional automatic damage to the battle group.

If a battle group's Magnitude is reduced to 0, the battle group immediately makes a **rout check**. This is a (average Willpower of the battle group + bonus from Drill) roll against difficulty (1 + points of Size that the battle group has lost during the scene), with a cumulative +1 to difficulty if the rout check was caused by a supernatural area-of-effect weapon or spell or if, during the battle, an allied battle group has been dissolved, one of the battle group's leaders or heroes has been killed.

If the rout check succeeds, the battle group's Size reduces by 1, and its Magnitude is reset based on its new Size. Any remaining damage from the attack that reduced the battle group's original Magnitude to 0 is applied to the new Magnitude, which can potentially cause a new rout check.

If the rout check fails, the battle group keeps its Size, but stays at Magnitude 0.[^battle-group-limbo] At the start of the battle group's next turn, the battle group dissolves, and its remaining fighters run or surrender as best they can. To represent attacks made against these fighters, the battle group can be treated as though it still exists, but it can't take any actions and gets -3 to Defense.

[^battle-group-limbo]: The is a best-guess interpretation of the unclear state of a battle group after a failed rout check.

A character who causes a battle group to lose a point of Size or to dissolve gets a Break bonus, as though they had Crashed an opponent.

Some rare battle groups have **perfect morale**. A battle group with perfect morale automatically succeeds at all rout checks and gets +3 Magnitude, but can't benefit from Rally for Numbers actions.

### Interacting with Battle Groups

An individual character can cover ground through the space occupied by members of a battle group, but this area counts as difficult terrain and you have to pay 1 Initiative per round that you do this.

### Commanding Battle Groups

If you're known and trusted by the members of a battle group, and you have some way to make yourself known to the members of that battle group, you can use one of these actions to command that battle group.

#### Order

**Defense** -1; **Flurry** no  
**Action** Simple; **Duration** Instant  
**Requirement** A battle group will follow your commands.

Declare an order and roll ([Charisma, Appearance, or Intelligence] + War) against difficulty 1, using Intelligence if you're not actively participating in the battle, Charisma if you're leading from the front and inspiring the troops, or Appearance if you're leading by example. If you succeed, the battle group follows your order on the next turn, and adds (total successes) to all of its dice pools for actions taken during that turn.

#### Rally

**Defense** -1; **Flurry** no  
**Action** Simple; **Duration** Instant  
**Requirement** A battle group will follow your commands, and it failed a rout check but hasn't yet dissolved.

Roll ([Charisma or Appearance] + War) against the difficulty of the failed rout check. If you succeed, the battle group recovers as if it had succeeded on its rout check.

#### Rally for Numbers

**Defense** -1; **Flurry** no  
**Action** Simple; **Duration** Instant  
**Requirement** A battle group will follow your commands, and it's suffered Magnitude damage.

Roll ([Charisma or Appearance] + War) against difficulty 1. The battle group gains (total successes ÷ 2, rounded down) Magnitude, up to the total possible for its average health levels and Size.

A battle group can only benefit from this action once per battle, plus once after each time it loses a point of Size.
