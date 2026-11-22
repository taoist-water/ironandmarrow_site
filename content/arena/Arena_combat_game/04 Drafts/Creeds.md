---
tags: [draft]
status: draft
source: Design doc v0.16
---

# Creeds (draft)

Oct 27, 2026 · @TheTao · *Draft for review. Nothing here is in the rules yet. Wave 1 is the first six Creeds; wave 2 adds seven more.*

## Why Creeds

Every warband currently draws on the same Action deck and the same 23 traits, so a cult and a band of witch-hunters play the same. Creeds give each warband an identity, the way Mordheim's warband lists do, without adding work during play. All the new depth sits in warband building. In play, each fighter still has 4 stats and at most 2 traits.

**What it replaces:** nothing. It is a layer on the warband builder. **What it solves:** warbands with no identity.

## How Creeds work

- Each warband picks one Creed before building.
- A Creed gives a **Creed rule** that is always on, a **restriction**, its **Sorcery access**, and **3 exclusive traits** only that Creed can take.
- Creed traits count toward the 2-trait limit per fighter. A Creed trait marked *Sorcery* also counts toward the Sorcery limits.
- Creed traits are never discounted.
- Every Creed has a ready-made 60-point list, so a new player can pick a Creed and start in under 2 minutes.

## The Creeds at a glance

| Creed | Plays as | Creed rule | Sorcery | Restriction |
| --- | --- | --- | --- | --- |
| Witch-Hunters | Counter-casters | +1 die against Sorcery fighters | None | Must include a Leader |
| Rift Cult | Sorcery-heavy, self-harm | Up to 4 Sorcery traits; can Channel with blood | Up to 4 | No Marksman or Defender |
| The Unburied | Slow, relentless | Opponents can't spend their Fatigue | Normal (2) | −1 Move; no Swift |
| Free Company | Best equipped | Gear traits cost 1 less | Max 1 | None |
| The Penitent | Pain fuels Wrath | Big hits on them give +1 Wrath | Prayers (2) | No Defender; no Shield |
| Gutter Kin | Wide objective swarm | 5 fighters; cheap, Glory-less Skirmishers | Normal (2) | No Brute; no Large models |
| *Wave 2* | | | | |
| Orc Warhost | Wrath every turn | Wrath options cost 1 less Wrath | Max 1 | No Defender |
| Goblin Rabble | Dirty tricks, hazards | Place a hazard token each round | Normal (2) | No Brute or Defender |
| Beastkin Herd | Ambush from the edges | One fighter enters later from an empty edge | Max 1 | No Marksman |
| Vampire Court | One superstar | Leader +1 die, heals by wounding | Normal (2) | Must include a Leader; max 3 fighters |
| Dwarf Hold | Immovable | Guard stays until the fighter acts | None | No Skirmisher, Swift or Shield |
| Elven Wardens | Speed and precision | +1 hex on every move | Normal (2) | No Brute |
| Infernal Host | Unholy resilience | Always save on 5+, whatever the angle | Normal (2) | No Gear traits; start at Wrath 3 |

## Witch-Hunters

**Creed rule: Burn the Witch.** +1 Attack die when attacking a fighter that has a Sorcery trait. On a 3-dice attack against Armour 4+, expected damage rises from 1.00 to 1.33.

**Restriction:** no Sorcery traits. The warband must include a Leader.

| Trait | Cost | Effect |
| --- | --- | --- |
| Blessed Steel | 3 | Sorcery cannot target this fighter |
| Brand of Faith | 2 | Once per game, ignore a Critical Injury |
| Torch | 3 | Ranged attack with 2 dice, range 2. A fighter it hits gains 1 Fatigue |

**Ready-made list (60):** Leader with Brand of Faith and Veteran 24, Duelist with Torch 18, Duelist with Blessed Steel 18.

**Risk:** the Creed rule does nothing in a game where no opponent takes Sorcery. Torch is the general-purpose tool: 2 dice against Armour 4+ hits at least once 75% of the time, and each Fatigue it gives lets any opponent raise their next 3-dice attack on that fighter from 1.00 to 1.33 damage. If Witch-Hunters lose most games against non-Sorcery warbands, give them +5 points.

## Rift Cult

**Creed rule: Gifts of the Rift.** The warband may take up to 4 Sorcery traits (still 1 per fighter). **Blood Offering:** when a fighter Channels, it may lose 1 Wound instead of discarding an Action card.

**Restriction:** no Marksman or Defender.

| Trait | Cost | Effect |
| --- | --- | --- |
| Grasping Limbs | 3 | Melee Kill Zone is all 6 adjacent hexes |
| Horrific | 3 | The first melee attack against this fighter each round rolls 1 fewer die |
| Rift-burst | 2 | When this fighter is taken out, every fighter adjacent to it takes 1 damage |

**Ready-made list (60):** Leader with Bolt 24, Duelist with Curse and Horrific 21, Skirmisher with Blink and Unshakeable 15. Three Sorcery traits.

**Maths:** Horrific turns the first 3-dice attack each round from 1.00 damage into 0.67. Blood Offering trades a Wound (a fifth of a 5-Wound Leader or Duelist) for a card; it matters most at high Wrath, when cards run short.

**Risk:** four Sorcery users plus Blink and Compel is the combo the rules already flag. Watch it first.

## The Unburied

**Creed rule: Unfeeling.** Opponents cannot spend Fatigue tokens on Unburied fighters. Fatigue still makes them Exhausted at 3.

**Restriction:** every fighter has −1 Move (minimum 2) and cannot take Swift.

| Trait | Cost | Effect |
| --- | --- | --- |
| Grave Chill | 2 | After this fighter makes a melee attack, the target gains 1 Fatigue |
| Rattling Bones | 2 | Saves on 4+ against ranged attacks |
| Corpse-feast | 3 | When this fighter takes out an enemy, it heals 1 Wound |

**Ready-made list (60):** Brute with Corpse-feast and Veteran 25, Defender with Grave Chill and Unshakeable 23, Skirmisher with Rattling Bones 12.

**Maths:** normally each Fatigue token an opponent spends is worth about +0.33 damage to them (Armour 4+ becoming 3+ lifts a 3-dice attack from 1.00 to 1.33). Unfeeling removes that, so an Unburied fighter can activate 3 times a round with only Exhaustion as the brake. The −1 Move is the price: a Defender moves 2, which makes objectives slow to reach.

**Risk:** a Brute activating 3 times a round is 4 dice × 3. If Unburied games swing on one fighter, cap repeat activations at 2.

## Free Company

**Creed rule: Well Equipped.** Gear traits cost 1 less (minimum 1).

**Restriction:** at most 1 Sorcery trait in the warband.

| Trait | Cost | Effect |
| --- | --- | --- |
| Crossbow | 3 | Ranged attack with 3 dice, range 4. Once per round |
| Hardened | 2 | Ignore the first Fatigue token spent against this fighter each round |
| Mercenary Contract | 3 | This fighter can be a second Brute |

**Ready-made list (60):** Leader with Shield 22, Duelist with Crossbow 18, Brute 20.

**Maths:** a warband of 4 fighters with one Gear trait each saves 4 points, about 7% of the budget. Crossbow gives a Duelist the Marksman's ranged dice at range 4 instead of 5.

**Risk:** two Brutes is the strongest melee core in the game (4 dice each, 5 Attacks to take out). Mercenary Contract may need to cost 5.

## The Penitent

**Creed rule: Mortification.** When one of your fighters loses 2 or more Wounds from a single attack, gain 1 Wrath. Sorcery is flavoured as prayers; the rules are unchanged.

**Restriction:** no Defender and no Shield.

| Trait | Cost | Effect |
| --- | --- | --- |
| Flagellant | 3 | At the start of its activation, this fighter may lose 1 Wound to gain +2 dice on its next Strike this activation |
| Martyr's Zeal | 3 | When this fighter is taken out, your warband gains 1 extra Wrath (3 in total) |
| Rallying Hymn (Sorcery) | 3 | Each friendly fighter within 2 hexes removes 1 Fatigue |

**Ready-made list (60):** Leader with Rallying Hymn 23, Brute with Flagellant 23, Skirmisher with Martyr's Zeal and Unshakeable 14.

**Maths:** a 3-dice attack deals 2 or more Wounds 26% of the time against Armour 4+ and 42% against Armour 3+. Over roughly 10 attacks a game against them, that is about 2–4 extra Wrath, so 2–4 extra activations. Flagellant trades 1 Wound for +0.67 expected damage.

**Risk:** this Creed is pillar 2 in its purest form, which also makes it the likeliest runaway. If the Penitent hit Wrath 8 by round 3, Mortification should trigger once per round at most.

## Gutter Kin

**Creed rule: Swarm.** The warband may have 5 fighters, and Skirmishers cost 8. **Vermin:** taking out a Gutter Kin Skirmisher scores no Glory (the Bounty still applies).

**Restriction:** no Brute and no Large models.

| Trait | Cost | Effect |
| --- | --- | --- |
| Pack Tactics | 3 | +1 Attack die if another friendly fighter is adjacent to the target |
| Envenomed | 3 | An enemy that loses Wounds to this fighter's attack also gains 1 Fatigue |
| Scurry | 2 | After this fighter survives an attack, it may move 1 hex |

**Ready-made list (60):** Leader with Pack Tactics 23, Skirmisher with Envenomed 11, Skirmisher with Scurry 10, Skirmisher 8, Skirmisher 8.

**Maths:** a Skirmisher (4 Wounds since v0.16) falls to 3 attacks on average. Without Vermin, five fragile fighters would be a Glory feeder for whoever sits next to them, which is kingmaking. With Vermin, killing a Skirmisher only denies an objective.

**Risk:** 5 fighters on Wrath 4 means each one activates less than once a round, which makes the rules' existing activation risk worse. The tie-break (fewer fighters lost) also works against them.

## Wave 2

Wave 2 is drafted on the same pattern but should be tested only after wave 1 settles. Thirteen Creeds make 78 different two-player pairings, so a bad wave 1 rule would spread into every one of them. Three of these needed a different mechanic from a wave 1 Creed they resemble: Goblins (hazards, not a swarm like Gutter Kin), Vampires (one superstar, not attrition like the Unburied) and the Infernal Host (resilience, not Sorcery like the Rift Cult). Mount access for each Creed is in the Mounts draft.

## Orc Warhost

**Creed rule: Born to Fight.** Wrath options that cost Wrath cost 1 less (minimum 0). Brutal Swing's Wrath Strike and Berserk's Taunt become free, and Berserk's Wrath Strike costs 1.

**Restriction:** no Defender. At most 1 Sorcery trait.

| Trait | Cost | Effect |
| --- | --- | --- |
| Big Cleaver | 4 | +1 die on Wrath Strikes |
| Headbutt | 2 | After this fighter's melee attack, Shove the target 1 hex |
| Warpaint | 3 | Once per round, re-roll one failed save |

**Ready-made list (60):** Brute with Big Cleaver and Unshakeable 25, Leader with Warpaint 23, Skirmisher with Headbutt 12.

**Maths:** 8 of the 40 Action cards have a Wrath option that costs Wrath (Brutal Swing and Berserk), so a 5-card hand holds 1.0 on average. A Brute with Big Cleaver making a free Wrath Strike rolls 7 dice: 2.33 damage against Armour 4+, enough to take out a 5-Wound Leader in a little over two attacks.

**Risk:** it solves the Wrath timing problem for Orcs only; everyone else still faces it. If Orcs win most games, Born to Fight should apply to Brutal Swing only.

## Goblin Rabble

**Creed rule: Dirty Tricks.** Once per round, when one of your Initiative cards is drawn, place a hazard token on an empty hex within 2 hexes of one of your fighters. A fighter entering a hazard takes 1 damage. You can have 3 hazards out at once; placing a fourth removes your oldest.

**Restriction:** no Brute or Defender.

| Trait | Cost | Effect |
| --- | --- | --- |
| Net | 3 | An enemy hit by this fighter's melee attack cannot Move on its next activation |
| Sneaky | 2 | Enemies cannot Riposte this fighter's attacks |
| Firepot | 3 | Ranged attack with 2 dice, range 3. Then place a hazard on an empty hex next to the target |

**Ready-made list (60):** Leader with Net and Veteran 25, Skirmisher with Firepot 13, Skirmisher with Sneaky 12, Skirmisher 10.

**Risk:** hazards are tokens that stay on the board, which adds bookkeeping and slows play. The cap of 3 keeps it bounded. Hazards block everyone, so watch for a Goblin player walling off one opponent for another's benefit.

## Beastkin Herd

**Creed rule: From the Wilds.** Hold one fighter off the board at deployment. The first time it activates, place it within 1 hex of any unoccupied edge, facing any direction, then activate it.

**Restriction:** no Marksman. At most 1 Sorcery trait.

| Trait | Cost | Effect |
| --- | --- | --- |
| Horns | 3 | When this fighter Charges, +1 die, and Shove the target 1 hex after the attack |
| Scent of Blood | 2 | +1 die against a fighter that has lost Wounds |
| Bray-howl (Sorcery) | 4 | Each enemy within 2 hexes gains 1 Fatigue |

**Ready-made list (60):** Leader with Bray-howl 24, Brute with Scent of Blood and Unshakeable 23, Skirmisher with Horns 13.

**Maths:** Advance and Lunge both offer a Charge (8 of the 40 cards), so a 5-card hand holds at least one 69% of the time.

**Risk:** at 4 players only edges 3 and 6 are empty, and each sits next to two seats. The ambush always lands near the same two players. Test whether those seats lose more often.

## Vampire Court

**Creed rule: Lord of the Night.** Your Leader costs 30, has +1 Attack die, and heals 1 Wound when its attack removes at least 1 Wound (once per round).

**Restriction:** must include a Leader. At most 3 fighters.

| Trait | Cost | Effect |
| --- | --- | --- |
| Mesmerise (Sorcery) | 3 | An enemy within 3 hexes cannot attack your Leader on its next activation |
| Night Wings | 3 | Ignores Obstruction and Pit hexes while moving |
| Thrall-bound | 1 | When this fighter is taken out, your Leader heals 1 Wound |

**Ready-made list (60):** Leader 30, Duelist with Thrall-bound and Unshakeable 17, Skirmisher with Mesmerise 13.

**Maths:** the Leader rolls 4 dice: 1.33 damage against Armour 4+, and at least 1 Wound 80% of the time, so it heals about once a round. Over 4 rounds that is up to 4 extra Wounds on a 5-Wound fighter.

**Risk:** healing makes games longer, which works against the speed target. A Vampire who is also the Glory leader will be very hard to bring down, so watch for a runaway.

## Dwarf Hold

**Creed rule: Stubborn.** A Dwarf fighter's Guard token stays until it Moves or Strikes, instead of clearing at the end of the round. Stubborn does not apply to Defenders.

**Restriction:** no Skirmisher, no Swift and no Shield. No Sorcery traits; Dwarves use runes instead.

| Trait | Cost | Effect |
| --- | --- | --- |
| Rune of Warding | 3 | Sorcery that targets this fighter is cancelled on a 4+ |
| Grudge | 2 | At deployment, pick an enemy fighter. +1 die against it |
| Shieldbearer | 3 | Adjacent friendly fighters save on 4+ against ranged attacks |

**Ready-made list (60):** Defender with Grudge 22, Leader with Rune of Warding 23, Duelist 15.

**Maths:** a Guarded fighter with Armour 4+ takes 0.75 damage per 3-dice attack instead of 1.00. A Guarded Defender (Armour 5+) would take 0.50, which is 8 attacks to take out, so Stubborn excludes Defenders. Attacks from the rear arc still save only on 6, which is the counter: 1.25 damage against a Guarded Dwarf from behind.

**Risk:** this is the Creed most likely to lock objectives, the risk the rules already flag. Record how often an objective held by a Dwarf changes hands.

## Elven Wardens

**Creed rule: Grace.** Whenever an Elf moves (the Move Basic Action or a Charge), it may move 1 more hex.

**Restriction:** no Brute.

| Trait | Cost | Effect |
| --- | --- | --- |
| Hawk-eye | 4 | Ranged attacks re-roll misses |
| Blade-dance | 3 | After this fighter Strikes, it may move 1 hex |
| Shadow Cloak | 2 | Ranged attacks against this fighter from more than 3 hexes away roll 1 fewer die |

**Ready-made list (60):** Marksman with Hawk-eye 19, Duelist with Blade-dance 18, Leader with Shadow Cloak and Unshakeable 23.

**Maths:** a Marksman's 3 ranged dice against Armour 4+ deal 1.00 damage; with Hawk-eye, 1.50. That is +50%, which is why it costs 4, not 3.

**Risk:** Grace plus Blade-dance means Elves strike and step away every turn, which is frustrating for opponents. If players complain, Blade-dance should cost 1 Fatigue.

## Infernal Host

**Creed rule: Unholy Flesh.** Infernal fighters always save on 5+. Guard, cover and rear arcs don't change it.

**Restriction:** no Gear traits. Your warband starts at Wrath 3 instead of 4.

| Trait | Cost | Effect |
| --- | --- | --- |
| Hellfire (Sorcery) | 4 | Ranged attack with 2 dice, range 3. Its hits cannot be saved |
| Burning Body | 2 | An enemy that attacks this fighter in melee and scores no hits takes 1 damage |
| Dread | 3 | An enemy that starts its activation next to this fighter gains 1 Fatigue |

**Ready-made list (60):** Brute with Dread and Unshakeable 24, Leader with Hellfire 24, Skirmisher with Burning Body 12.

**Maths:** attacking an Infernal fighter from behind deals 1.00 damage instead of 1.25, but a Guarded one also takes 1.00 instead of 0.75. Facing matters less against them, both ways. Hellfire deals 1.00 damage at range 3, the same as a 3-dice melee Strike. Starting at Wrath 3 costs them 1 of 4 activations in round 1.

**Risk:** Burning Body gives the attacker 1 Wrath for the miss as well as 1 damage. Check that the two don't cancel out.

## Pillar and multiplayer check

| Creed | Pillar risk | Multiplayer risk |
| --- | --- | --- |
| Witch-Hunters | None | Pulls attacks onto Sorcery warbands, not onto the leader |
| Rift Cult | Speed, if Channelling slows turns | Blink and Compel let it reach any rear arc |
| The Unburied | Pillar 1: fewer tense Fatigue choices | None found |
| Free Company | None | None found |
| The Penitent | Pillar 2 taken to a runaway | A Penitent leader is hard to drag down |
| Gutter Kin | Activation downtime per fighter | Glory feeding, handled by Vermin |
| Orc Warhost | None | None found |
| Goblin Rabble | Speed: hazard tokens to track | Hazards can wall off one opponent |
| Beastkin Herd | None | The ambush always lands near the same two seats at 4 players |
| Vampire Court | Speed: healing lengthens games | A healing Glory leader is hard to drag down |
| Dwarf Hold | Speed: Guarded fighters last longer | Objective lock feeds a runaway |
| Elven Wardens | None | Hit-and-run frustration |
| Infernal Host | None | None found |

## Playtest checks

- [x] Calculation: every ready-made list, waves 1 and 2, costs exactly 60 and breaks no limit (checked 27 Oct).
- [ ] Build time: a new player builds from scratch in 10 minutes or less, and from a ready-made list in 2 minutes or less.
- [ ] 4-player games: record which Creed wins. Any Creed winning more than 40% of games is too strong.
- [ ] Penitent: record Wrath at the start of each round. Hitting 8 before round 4 means Mortification needs a cap.
- [ ] Gutter Kin: record Glory scored against them. Near zero means Vermin is too protective.
- [ ] Wave 2, after wave 1 settles: Dwarf Hold, record how often an objective held by a Dwarf changes hands; Vampire Court, record game length.

## Decisions needed

1. Adopt Creeds as a layer on the warband builder.
2. Approve, change or cut each of the wave 1 Creeds.
3. Test wave 2 only after wave 1 settles.
4. Names: keep these, or rename to fit your world.
