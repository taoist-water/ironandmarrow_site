---
tags: [rules, warbands]
status: draft
source: Design doc v0.16
---

# Fighters and Warbands

Every fighter is a chassis plus up to two traits, and a warband is 3–4 fighters built from 60 points. The models are only stand-ins, so any miniature that fits the setting works.

**Building rules**

- A warband is 3–4 fighters costing 60 points or less.
- At most one Leader and one Brute.
- Each fighter takes up to 2 traits from any category. At most 1 of them can be Sorcery, and a warband can have at most 2 Sorcery traits.
- Traits are one rule type, sorted into three categories so players can browse by theme: **Gear** (what the fighter carries), **Skills** (what it has trained in) and **Sorcery** (spells, prayers, witchcraft and blood rites).

**Chassis (first-draft costs)**

| Chassis | Move | Attack | Armour | Wounds | Cost | Attacks to take out | Role |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Brute | 3 | 4 | 4+ | 5 | 20 | 5.0 | Hits hard, soaks damage |
| Defender | 3 | 2 | 5+ | 4 | 20 | 6.0 | Holds objectives |
| Leader | 4 | 3 | 4+ | 5 | 20 | 5.0 | While alive: hand size +1 |
| Duelist | 4 | 3 | 4+ | 5 | 15 | 5.0 | All-rounder |
| Marksman | 3 | 2 (ranged 3, range 5) | 3+ | 4 | 15 | 3.0 | Ranged pressure |
| Skirmisher | 5 | 2 | 3+ | 4 | 10 | 3.0 | Objective grabber, flanker |

Attacks to take out = Wounds ÷ expected damage from one 3-dice attack (see [[Combat]]: 1.33 against Armour 3+, 1.00 against 4+, 0.67 against 5+). The target is 3–5. It was 2–4 until v0.16, when playtests 3 and 4 showed fighters dying in 2–3 attacks once Critical Injuries, Fatigue spends and Wrath Strikes were in play, so every chassis except the Brute and Defender gained 1 Wound. The Defender sits above the target by design, which is why it is limited to holding ground.

**Gear**

| Trait | Cost | Effect |
| --- | --- | --- |
| Shield | 3 | Saves on 3+ when Guarded |
| Polearm | 4 | Melee Kill Zone extends 2 hexes into the front arc |
| Sweeping Weapon | 3 | Cleave without losing a die |
| Great Weapon | 5 | +1 Attack die in melee. The fighter cannot Guard |
| Throwing Weapons | 3 | Ranged attack with 2 dice, range 3 |
| Hook | 2 | After a melee Strike that hits, turn the target to face any direction |
| Field Kit | 2 | Once per game, when this fighter Recovers it also heals 1 Wound |

**Skills**

| Trait | Cost | Effect |
| --- | --- | --- |
| Swift | 3 | +1 Move |
| Tough | 3 | +1 Wound. Cannot take a fighter above 5 Wounds |
| Relentless | 3 | First repeat activation each round gains no Fatigue |
| Unshakeable | 1 | Cannot be Shoved |
| Veteran | 2 | Once per round, re-roll 1 Attack die |
| Bodyguard | 3 | When an adjacent friendly fighter is targeted, this fighter becomes the target instead, if it is in the attacker's Kill Zone |
| Backstabber | 2 | On rear-arc attacks, natural 5s count as 6s for Critical Injuries |
| Riposte Master | 2 | Riposte does not lose a die |

**Sorcery**

**Channel.** A fighter with a Sorcery trait can Channel during its activation: discard an Action card instead of resolving one of its options, and use the Sorcery instead. Each fighter can Channel once per round. Channelling costs a card, not Wrath, so it doesn't add to the Wrath timing problem.

| Trait | Cost | Effect |
| --- | --- | --- |
| Bolt | 4 | Ranged attack with 3 dice, range 4 |
| Ward | 2 | A friendly fighter within 3 hexes gains Guard |
| Blink | 4 | Place this fighter in an empty, non-Pit hex within 3, facing any direction |
| Curse | 3 | An enemy within 4 hexes, in line of sight, gains 1 Fatigue |
| Compel | 3 | Turn an enemy within 3 hexes to face any direction |
| Mend | 4 | Another friendly fighter within 2 hexes heals 1 Wound |
| Empower | 2 | A friendly fighter within 2 hexes gets +1 die on its next Strike this round |

**Pricing maths**

- **Shield.** A Guarded fighter with Armour 4+ takes 0.75 damage per 3-dice attack; with a Shield, 0.50. That is −33%, but only after spending an activation on Guard.
- **Great Weapon.** A Duelist goes from 3 to 4 dice, so its damage rises from 1.00 to 1.33 per attack against Armour 4+. That is Brute output for 5 points.
- **Veteran.** A 3-dice attack against Armour 4+ has at least one miss 87.5% of the time. The re-roll adds 0.875 × ½ × ⅔ ≈ 0.29 damage, on one attack per round.

**Left out on purpose**

- **No Heavy Armour.** A Duelist at Armour 5+ and 5 Wounds would take 7.5 attacks to take out, well above the 3–5 target, and it would add to the Armour 5+ objective risk.
- **Tough is capped at 5 Wounds,** so it can't create a 6-Wound fighter. Since v0.16 only a Marksman or Skirmisher can use it.
- **Mend can't target the fighter itself,** so a Defender can't heal itself every round and become impossible to dislodge.

**Footprint.** Fighters on bases up to about 40 mm take 1 hex. Large models take 3 hexes, cost +10, and cannot take Swift.

**Example warbands (60 points)**

- **Wide (4 fighters):** Leader 20, Duelist 15, Skirmisher with Swift 13, Skirmisher with Hook 12.
- **Elite (3 fighters):** Brute with Veteran 22, Leader with Mend 24, Skirmisher with Blink 14.
