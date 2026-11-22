---
tags: [draft]
status: draft
source: Design doc v0.16
---

# Codex Fork (draft)

Nov 1, 2026 · @TheTao · *A fork of the design for deep customisation. It does not change the core rules; it adds a layer that replaces the warband builder when both players agree to play Codex rules.*

## What this fork is

The core game is beer-and-chips: 60 points, two one-line traits per fighter, one game in about an hour. The Codex fork sets that aside and goes for the depth of the retro games: long menus of magic items and spells (Warhammer Fantasy Battle, the editions before Age of Sigmar), and skill tables with warband access (Mordheim and Necromunda). The aim is enough choice that a warband on the table looks and plays like the miniatures and the Creed its owner chose.

**Sources, named.** Taken as structure, not text: magic item categories, points allowances by rank and one-of-each item limits (WFB); spell lores with casting values and dispelling (WFB); skill tables with Creed access and heroes versus followers (Mordheim, Necromunda); weapon profiles that modify saves and deal extra damage (Necromunda). Every item, spell and skill below is original.

**What it replaces.** The 2-trait cap and the three short trait lists. Everything else in the core rules stands: cards, Wrath, Fatigue, combat, objectives, Creeds.

## Pillar check

| Pillar | Effect of the fork |
| --- | --- |
| Speed and casual play | **Suspended by choice.** Expect about 90 minutes at 2 players and 2–2.5 hours at 4 (a target to test, not a measurement). |
| 1. Every activation is a tense choice | Kept. Casting and dispelling add two more card decisions per round. |
| 2. Losing players stay dangerous | **At risk.** A strong list can outclass a weak one before the first card is played, and Wrath catch-up can't close a gap built at the list stage. |
| 3. Any models, one setting | Strengthened. Equipment and items are meant to match what the model carries. |
| 4. Multiplayer without kingmaking | **At risk.** In 3–4 player games, any opponent can dispel a spell, so a player can choose whom to protect. |

## The new levers

The core engine has four stats and one Wound per hit, so most items would collapse into "+1 die". The fork adds three levers, used only in Codex games:

- **Save modifier.** "Target saves 1 worse" moves its save from 5+ to 6; "2 worse" means no save. Guarded fighters and cover improve the save first, then the modifier applies.
- **Damage 2.** Each uncancelled hit removes 2 Wounds instead of 1.
- **Ward save.** After normal saves, roll once more for each uncancelled hit; a roll that meets the ward cancels it. No modifier ever changes a ward save.

**Armour cap.** Equipment and magic items can't take a fighter's Armour above 5+. At Armour 6+ a 4-Wound fighter takes 12 attacks to take out, three times the core target. Fatigue spends can still raise Armour during an attack, as in the core rules.

## Pricing anchors

Every cost below comes from these, measured against a 3-dice attack on a 4-Wound, Armour 4+ fighter with a 5+ save (1.00 damage per attack, 4 attacks to take it out). Once-per-game effects cost about a third of the permanent version.

| Lever | Effect | Points |
| --- | --- | --- |
| +1 Attack die | 1.00 to 1.33 damage | 4 |
| Target saves 1 worse | 1.00 to 1.25 damage | 3 |
| Target saves 2 worse | 1.00 to 1.50 damage | 7 |
| Re-roll misses | 1.00 to 1.50 damage | 6 |
| Damage 2 | 1.00 to 2.00 damage | 12 |
| +1 Wound | 4 to 5 attacks to take out | 4 |
| Ward 6+ | 4 to 4.8 attacks | 3 |
| Save 4+ instead of 5+ | 4 to 5.3 attacks | 5 |
| Armour +1 (4+ to 5+) | 4 to 6 attacks | 8 |
| Ward 5+ | 4 to 6 attacks | 8 |
| +1 Move | — | 3 |

## Building a Codex warband

- **Budget:** 100 points for 3–5 fighters, including all equipment, skills and magic items.
- **Lord** (rank; Mordheim's heroes and henchmen, adapted): your Leader. 3 skills and up to 30 points of magic items.
- **Heroes** (rank): up to 2, any chassis, +5 points each. 2 skills and up to 15 points of magic items.
- **Followers** (rank): everyone else. Equipment only; no skills and no magic items.
- **Skills** cost 3 points each and come from the skill tables your Creed can use.
- **Magic items:** at most one per category per fighter, and each item at most once in your warband (WFB's rule).
- **Equipment:** any amount within points. Every fighter has a hand weapon for free.
- **Creed:** you still pick one, and it still gives its Creed rule and restriction. In Codex games, its three exclusive traits become skills only that Creed can take.
- **Model your kit.** What the model carries should match its equipment where possible, so opponents can read the warband from the table.

## Equipment

**Melee weapons**

| Weapon | Cost | Profile |
| --- | --- | --- |
| Hand weapon | Free | No modifiers |
| Paired weapons | 4 | +1 Attack die. Can't use a shield |
| Spear | 2 | +1 die on Ripostes |
| Halberd | 3 | Target saves 1 worse. Two-handed |
| Great weapon | 5 | +1 Attack die and target saves 1 worse. Two-handed; the fighter can't Guard |
| Flail | 3 | +2 dice on its first attack each round, −1 die after that |
| Polearm | 4 | Melee Kill Zone extends 2 hexes into the front arc. Two-handed |

**Ranged weapons** (front arc, line of sight)

| Weapon | Cost | Profile |
| --- | --- | --- |
| Sling | 2 | 2 dice, range 3 |
| Throwing knives | 3 | 2 dice, range 3. +1 die from the target's rear arc |
| Short bow | 3 | 2 dice, range 5 |
| Longbow | 5 | 3 dice, range 6. Can't be used in an activation in which the fighter moved |
| Crossbow | 5 | 3 dice, range 5, target saves 1 worse. Once per round |
| Javelins | 2 | 3 dice, range 3. Once per game |

**Armour and shields**

| Item | Cost | Profile |
| --- | --- | --- |
| Shield | 3 | Saves on 3+ when Guarded. Needs a free hand |
| Light armour | 3 | Saves on 4+ against ranged attacks |
| Heavy armour | 4 | Saves on 4+. −1 Move |
| Barding | 3 | A mounted fighter's mount: +1 Wound. Needs a Mount from the Mounts draft |

## Skill tables

Each table has six skills, numbered so that a future campaign can roll for advances, as Mordheim does. Your Creed decides which tables your Lord and Heroes can use (see Creed access). Skills cost 3 points each.

**Combat**

| d6 | Skill | Effect |
| --- | --- | --- |
| 1 | Riposte Master | Riposte doesn't lose a die |
| 2 | Weapon Master | Pick one melee weapon type: +1 die when using it |
| 3 | Disarm | An enemy this fighter hits rolls 1 fewer die on its next attack |
| 4 | Killing Stroke | In melee, natural 5s count as 6s for Critical Injuries |
| 5 | Parry | Once per round, cancel one hit against this fighter before saves, if the attacker is in its front arc |
| 6 | Duellist's Eye | Re-roll one Attack die on every attack |

**Agility**

| d6 | Skill | Effect |
| --- | --- | --- |
| 1 | Swift | +1 Move |
| 2 | Leap | Can move over one Obstruction hex per move |
| 3 | Dodge | Ranged attacks against this fighter roll 1 fewer die |
| 4 | Sprint | Once per round, +2 hexes on a move; the fighter gains 1 Fatigue |
| 5 | Light-footed | Can turn to face any direction at any time, even outside a move |
| 6 | Quick Reflexes | Can Riposte attacks from its rear arc |

**Strength**

| d6 | Skill | Effect |
| --- | --- | --- |
| 1 | Tough | +1 Wound (Codex cap: 5 Wounds) |
| 2 | Mighty Blow | Melee targets save 1 worse |
| 3 | Unshakeable | Can't be Shoved |
| 4 | Iron Hide | Ignore the first Critical Injury drawn against it each game |
| 5 | Bull Rush | When it Charges, Shove the target 1 hex before Striking |
| 6 | Iron Grip | Ignores the "can't Guard" drawback of a great weapon |

**Cunning**

| d6 | Skill | Effect |
| --- | --- | --- |
| 1 | Backstabber | On rear-arc attacks, natural 5s count as 6s for Critical Injuries |
| 2 | Ambush | Deploys after every other fighter, anywhere within 3 hexes of its own edge |
| 3 | Venom | An enemy that loses Wounds to this fighter also gains 1 Fatigue |
| 4 | Slippery | Opponents need 2 Fatigue tokens to lower this fighter's Armour by 1 |
| 5 | Scavenger | Once per game, draw 2 Action cards as a free action |
| 6 | Lurker | Can't be targeted by ranged attacks from more than 3 hexes away until it attacks |

**Command** (Lord and Heroes only)

| d6 | Skill | Effect |
| --- | --- | --- |
| 1 | Rally | Once per round, remove 1 Fatigue from a friendly fighter within 3 hexes |
| 2 | Tactician | +1 hand size (stacks with the Leader's) |
| 3 | War Leader | Your Seize costs 1 Wrath instead of 2 |
| 4 | Bodyguard | When an adjacent friendly fighter is targeted, this fighter becomes the target instead, if it is in the attacker's Kill Zone |
| 5 | Battle Cry | Once per game, a War Cry as a free action at the start of its activation |
| 6 | Vengeful | When a friendly fighter within 3 hexes is taken out, gain 1 extra Wrath |

**Arcane**

| d6 | Skill | Effect |
| --- | --- | --- |
| 1 | Wizard | Knows 2 spells from one lore its Creed can use, and can cast (see Magic) |
| 2 | Adept | Needs Wizard. Knows 2 more spells and gets +1 to casting rolls |
| 3 | Spell-thief | After it dispels a spell, it may cast that spell once this game |
| 4 | Ward-weaver | +1 to its dispel rolls and to those of friendly fighters within 3 hexes |
| 5 | Blood Magic | Can lose 1 Wound to add +2 to a casting roll |
| 6 | Familiar | Once per round, re-roll a casting or dispel roll |

## Magic

Casting and dispelling follow WFB's magic phase, adapted to Action cards.

- **Casting.** A Wizard casts during its activation instead of resolving a card option. Discard an Action card, name a spell it knows and roll 2d6 (+1 for Adept). Meet the spell's casting value and it works. Each Wizard casts once per round.
- **Dispelling.** When a spell would work, one opponent may discard an Action card and roll 2d6. Equal to or above the casting total cancels it. With 3–4 players, the opponent nearest clockwise from the caster decides first, then the next.
- **Double 6** on a casting roll can't be dispelled. **Double 1** fails, and the Wizard takes 1 damage with no save.
- **Prayers** (the Faith lore) can't be dispelled, but a failed prayer costs 1 Wrath.

**Odds.** Chance 2d6 reaches a casting value:

| Bonus | 5 | 6 | 7 | 8 | 9 | 10 |
| --- | --- | --- | --- | --- | --- | --- |
| +0 | 83% | 72% | 58% | 42% | 28% | 17% |
| +1 | 92% | 83% | 72% | 58% | 42% | 28% |
| +2 | 97% | 92% | 83% | 72% | 58% | 42% |

A dispeller has the same odds of matching the total, so a spell cast on a total of 8 is dispelled 42% of the time. Big spells are both harder to cast and easier to stop.

## Spell lores

Ranges and areas are in hexes. Six lores with six spells each; a Wizard learns spells from lores its Creed can use.

**Lore of Flame**

| Spell | Value | Effect |
| --- | --- | --- |
| Flame Dart | 5 | Ranged attack, 2 dice, range 5 |
| Kindle Rage | 6 | A friendly fighter within 4 gets +1 die on its next Strike |
| Wall of Fire | 7 | Two adjacent empty hexes within 6 become hazards until the end of the round |
| Searing Ray | 7 | A 2-dice attack against every fighter in a straight line of 4 hexes from the caster |
| Immolate | 9 | Ranged attack, 4 dice, range 4; the target saves only on 6 |
| Inferno | 10 | A 2-dice attack against every fighter within 2 hexes of a point within 6 |

**Lore of Shadow**

| Spell | Value | Effect |
| --- | --- | --- |
| Veil | 5 | A friendly fighter within 6 can't be targeted by ranged attacks until its next activation |
| Shadow Step | 6 | Place a friendly fighter within 6 in an empty hex within 3 of it, facing any direction |
| Gloom | 6 | An enemy within 6 rolls 1 fewer Attack die until the end of the round |
| Phantasm | 7 | Turn an enemy within 6 to face any direction |
| Creeping Dread | 8 | An enemy within 6 gains 2 Fatigue |
| Unseen Blade | 9 | A friendly fighter within 6 makes a Strike at once, counting as from the target's rear arc |

**Lore of Bone**

| Spell | Value | Effect |
| --- | --- | --- |
| Grave Chill | 5 | An enemy within 4 gains 1 Fatigue |
| Bone Armour | 6 | A friendly fighter within 4 saves on 4+ until the end of the round |
| Deathly Hush | 6 | Enemies within 3 can't Riposte until the end of the round |
| Wither | 7 | An enemy within 6 loses 1 Wound, no save |
| Life Drain | 8 | Ranged attack, 3 dice, range 4; the caster heals 1 Wound per Wound removed (at most 2) |
| Raise the Fallen | 9 | Once per game: a taken-out friendly Follower returns with 1 Wound, within 1 hex of the caster |

**Lore of Blood**

| Spell | Value | Effect |
| --- | --- | --- |
| Crimson Frenzy | 5 | A friendly fighter within 4 gets +2 dice on its next Strike, then gains 1 Fatigue |
| Blood Boil | 6 | An enemy within 4 and the caster each lose 1 Wound, no saves |
| Sanguine Pact | 6 | Gain 1 Wrath; the caster loses 1 Wound |
| Open Veins | 7 | An enemy within 6 draws a Critical Injury card |
| Haemorrhage | 8 | A 2-dice attack against every enemy within 2 of the caster |
| Red Harvest | 10 | Until the end of the round, friendly fighters heal 1 Wound whenever they take out an enemy |

**Lore of the Wild**

| Spell | Value | Effect |
| --- | --- | --- |
| Beast Speed | 5 | A friendly fighter within 6 gets +2 Move on its next move |
| Thornbind | 6 | An enemy within 6 can't move until the end of its next activation |
| Feral Hide | 6 | A friendly fighter within 4 gets Armour +1 (to 5+ at most) until the end of the round |
| Savage Roar | 7 | Shove every enemy within 3 of the caster 1 hex directly away from it |
| Swarm | 7 | Ranged attack, 3 dice, range 6, ignoring Guard and cover |
| Wild Fury | 9 | Friendly fighters within 3 get +1 die on Strikes until the end of the round |

**Lore of Faith** (prayers: can't be dispelled; a failed prayer costs 1 Wrath)

| Prayer | Value | Effect |
| --- | --- | --- |
| Blessing | 5 | A friendly fighter within 4 re-rolls failed saves until the end of the round |
| Smite | 6 | Ranged attack, 3 dice, range 4; +1 die against a Wizard |
| Martyr's Strength | 6 | Opponents can't spend a friendly fighter's Fatigue until the end of the round (fighter within 4) |
| Sanctuary | 7 | A friendly fighter within 4 can't be targeted until its next activation |
| Purge | 7 | End one spell effect, or discard a Critical Injury kept by a friendly fighter within 4 |
| Divine Wrath | 9 | A 2-dice attack, no saves, against every enemy within 2 of the caster |

## Magic items

One per category per fighter, each at most once per warband. Lord up to 30 points, Heroes up to 15.

**Magic weapons**

| Item | Cost | Effect |
| --- | --- | --- |
| Duellist's Rapier | 6 | Re-roll misses |
| Hungering Blade | 6 | When its attack removes Wounds, the bearer heals 1 (once per round) |
| Blade of Ruin | 7 | Targets save 2 worse |
| Frostbitten Edge | 4 | An enemy it damages gets −1 Move until the end of the next round |
| Headsman's Axe | 8 | Natural 5s and 6s count for Critical Injuries. Two-handed |
| Butcher's Cleaver | 12 | Damage 2. Two-handed |

**Magic armour** (Armour can't go above 5+)

| Item | Cost | Effect |
| --- | --- | --- |
| Warden's Helm | 3 | Ignore the first Critical Injury drawn against the bearer each game |
| Cloak of Dusk | 3 | Ranged attacks from more than 3 hexes away roll 1 fewer die |
| Thorned Mail | 4 | An enemy that attacks the bearer in melee and scores no hits takes 1 damage |
| Bonechain Hauberk | 5 | Saves on 4+, no Move penalty |
| Mirror Shield | 6 | Shield. Spells that target the bearer fail on a 4+ |
| Starforged Plate | 8 | Armour +1 (to 5+ at most), no Move penalty |

**Talismans**

| Item | Cost | Effect |
| --- | --- | --- |
| Lucky Coin | 2 | Once per game, re-roll any one die |
| Bloodstone | 3 | The first time each game the bearer would be taken out, it stays with 1 Wound |
| Charm of Warding | 3 | Ward 6+ |
| Amulet of Iron | 4 | Spells that target the bearer fail on a 5+ |
| Seal of Mercy | 4 | Cards kept with the bearer from Critical Injuries are discarded at the end of each round |
| Talisman of the Last Stand | 8 | Ward 5+ |

**Arcane items** (Wizards only)

| Item | Cost | Effect |
| --- | --- | --- |
| Power Stone | 3 | Once per game, +2 to a casting roll |
| Grimoire | 4 | Knows 1 extra spell |
| Dispel Scroll | 4 | Once per game, dispel a spell automatically (not a double 6) |
| Spirit Familiar | 4 | Once per round, cast from a friendly fighter within 3 as if the Wizard stood there |
| Blood Chalice | 4 | When a fighter within 3 is taken out, +2 to the Wizard's next casting roll |
| Staff of Channelling | 6 | +1 to all casting rolls |

**Enchanted items**

| Item | Cost | Effect |
| --- | --- | --- |
| Potion of Strength | 2 | Once per game, +2 dice on one attack |
| Smoke Bomb | 3 | Once per game, when an enemy declares an attack on the bearer, move it 1 hex first; the attack fails if the bearer leaves the Kill Zone |
| Healing Draught | 3 | Once per game, as its activation, the bearer heals 2 Wounds |
| Boots of Striding | 4 | +1 Move, and Step moves 2 hexes |
| Horn of Dread | 4 | Once per game, every enemy within 2 hexes gains 1 Fatigue |
| Hand of Glory | 4 | Once per game, take an activation when one of your Initiative cards would have been the last one drawn this round |

**Banners** (one per warband; the bearer is a Hero or Follower, not the Lord)

| Item | Cost | Effect |
| --- | --- | --- |
| Banner of Defiance | 4 | Friendly fighters within 2 of the bearer can't be Shoved |
| War Banner | 5 | Friendly fighters within 2 roll +1 die on Ripostes |
| Rallying Standard | 5 | Friendly fighters within 3 remove 1 extra Fatigue at the end of each round |
| Banner of Shadows | 5 | Ranged attacks against friendly fighters within 2 roll 1 fewer die |
| Grim Totem | 5 | Enemies within 2 of the bearer can't Guard |
| Banner of Fury | 6 | Once per game, gain 1 Wrath |

## Creed access

Each Creed opens three skill tables at most, and its lores. That is where the identity lives: two warbands with the same chassis still play differently because of what they can reach. Dwarves never cast; their runesmiths carry two Talismans instead.

| Creed | Skill tables | Lores | Relic (Lord only) |
| --- | --- | --- | --- |
| Witch-Hunters | Combat, Command, Cunning | Faith | **Brand of the Pyre** (5): +2 dice against Wizards |
| Rift Cult | Arcane, Strength, Cunning | Flame, Blood | **Eye of the Rift** (6): +1 to casting; a miscast also hits every fighter within 1 |
| The Unburied | Strength, Command, Arcane | Bone | **Crown of the Barrow** (6): friendly Followers within 3 ignore their first Critical Injury each game |
| Free Company | Combat, Agility, Command | Flame or Shadow (hired Wizard) | **Paymaster's Purse** (5): once per game, gain 1 Wrath and draw 1 card |
| The Penitent | Strength, Combat, Command | Faith | **Scourge of Contrition** (5): when the bearer loses Wounds, +1 die on its next Strike |
| Gutter Kin | Agility, Cunning | Shadow | **Rat-king's Tail** (4): Followers within 2 of the bearer can Step 2 hexes |
| Orc Warhost | Strength, Combat, Command | Wild | **Boss Choppa** (7): +1 die, and Wrath Strikes cost 1 less Wrath again |
| Goblin Rabble | Cunning, Agility, Arcane | Shadow | **Sneakin' Hood** (4): the bearer can't be targeted from more than 2 hexes away |
| Beastkin Herd | Strength, Agility | Wild | **Herdstone Shard** (5): the ambushing fighter may enter on any edge, occupied or not |
| Vampire Court | Combat, Command, Arcane | Bone, Blood | **Signet of the Night** (6): the Leader's healing works twice per round |
| Dwarf Hold | Combat, Strength, Command | None (two Talismans allowed) | **Ancestor Rune** (6): Ward 5+ against spells and ranged attacks |
| Elven Wardens | Agility, Combat, Arcane | Shadow, Wild | **Moonbow** (6): longbow that can be used after moving |
| Infernal Host | Strength, Arcane | Flame, Blood | **Brand of the Pit** (6): the bearer's melee attacks deal Damage 2 on natural 6s |

## Example Codex warband: Witch-Hunters (100 points)

| Fighter | Rank | Kit | Points |
| --- | --- | --- | --- |
| Leader (20) | Lord | Crossbow 5, Parry 3, Rally 3, Lurker 3, Brand of the Pyre 5, Charm of Warding 3 | 42 |
| Duelist (15) | Hero (+5) | Paired weapons 4, Weapon Master 3, Disarm 3, Lucky Coin 2 | 32 |
| Skirmisher (10) | Follower | Throwing knives 3, light armour 3 | 16 |
| Skirmisher (10) | Follower | — | 10 |

Total: 100. The Lord's magic items come to 8 of 30, and the Hero's to 2 of 15.

## Risks

- **List strength decides games.** Fifty-odd items and skills give combinations that can't all be playtested. Some will be far better than their cost. Fix later with restricted lists, not rule changes.
- **Pillar 2 weakens.** Wrath catch-up works inside a game; it can't rescue a much weaker list.
- **Kingmaking by dispel.** In 3–4 player games, an opponent can choose to let a spell through when it hits a rival.
- **Damage 2 and Critical Injuries stack.** A Butcher's Cleaver hit that also crits can take a 4-Wound fighter out in one blow. That is the old-school feel, but it ends games early.
- **Flat skill price.** Every skill costs 3. Weapon Master (+1 die) sits 1 point under its anchor, justified only by working with one weapon type. Watch whether it appears in most lists.
- **Bookkeeping.** Each fighter needs a roster line or card listing its kit. Codex fighter cards will be needed.
- **Healing and wards lengthen games.** Hungering Blade, Life Drain, Bloodstone and the ward saves all push attacks-to-take-out above the core target of 2–4.

## Playtest checks

- [ ] Build time: how long does a new player take to build a 100-point Codex warband? Over 30 minutes means the menus need ready-made lists per Creed.
- [ ] Record game length at 2 and 4 players against the 90-minute and 2.5-hour targets.
- [ ] Record every magic item and skill taken across games. Anything in more than half of all lists is underpriced; anything never taken is overpriced or dull.
- [ ] Count spells cast, dispelled and miscast per game.
- [ ] 3–4 players: record who chose to dispel which spells, and whether dispels protected the leader or a rival.

## Decisions needed

1. Adopt the Codex fork as an optional layer, kept apart from the core game.
2. The three new levers (save modifiers, Damage 2, ward saves) and the Armour 5+ cap from kit.
3. The casting and dispelling system.
4. Approve, change or cut items, spells and skills; and whether each Creed should get more relics.
