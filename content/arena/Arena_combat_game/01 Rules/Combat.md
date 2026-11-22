---
tags: [rules, combat]
status: draft
source: Design doc v0.16
---

# Combat

Combat is SAGA's two-roll structure applied to individual fighters: roll to hit against the target's Armour, then the target rolls flat saves. Each uncancelled hit removes 1 Wound. All dice are d6.

1. **Target.** The target must be in the attacker's Kill Zone. The default melee Kill Zone is the 3 hexes in the fighter's front arc. Ranged fighters use their range in hexes, within the front arc and line of sight.
2. **Hit.** Roll the attacker's Attack dice. Each die equal to or above the target's Armour is a hit. A natural 6 always hits; a natural 1 always misses.
3. **Save.** The target rolls one die per hit. Each 5+ cancels a hit. A Guarded fighter, or one in cover against ranged attacks, saves on 4+. An attack from the target's rear arc means it saves only on 6. Saves cancel hits from the lowest roll up, so natural 6s are cancelled last.
4. **Damage.** Each uncancelled hit removes 1 Wound. If at least one uncancelled hit is a natural 6, the target also draws a Critical Injury card.
5. **Whiff.** If no dice hit, the attacker's warband gains 1 Wrath.

Armour is the stat that matters most, so the save threshold stays flat and changes only with the situation (Guard, cover, rear arc). Facing sets each fighter's 3-hex front arc and 3-hex rear arc. **Turning is free while moving.** During a move, a fighter can turn to face any direction at any point, at no cost in movement. A fighter can step into any adjacent hex whatever its facing. To turn without moving, a fighter needs an option that says turn, such as Turn, then Strike.

**Expected damage from a 3-dice attack**

| Target Armour | Normal (save 5+) | Guarded (save 4+) | From rear (save 6) |
| --- | --- | --- | --- |
| 3+ | 1.33 | 1.00 | 1.67 |
| 4+ | 1.00 | 0.75 | 1.25 |
| 5+ | 0.67 | 0.50 | 0.83 |

Against Armour 4+ and 5 Wounds, a fighter goes down to 5 normal attacks, or 4 from the rear; Critical Injuries bring that to about 4.6. Fighters with more than 5 Wounds should not exist. Armour 5+ halves incoming damage compared to 3+, so it needs to be priced heavily. A 3-dice attack against Armour 4+ whiffs 12.5% of the time; against Armour 5+, 30%.

**Critical Injuries**

A 3-dice attack against Armour 4+ now causes a Critical Injury 35% of the time (4 dice: 46%; from the rear: 39%). Under the old rule, two uncancelled 6s, it was 3.4%. The deck has 13 cards:

| Card | Copies | Effect |
| --- | --- | --- |
| Grievous Wound | 2 | The fighter loses 1 more Wound. Then discard |
| Cracked Skull | 2 | The fighter gains 2 Fatigue. Then discard |
| Severed Hand | 2 | −1 Attack die for the rest of the game. Keep with the fighter |
| Hamstrung | 2 | −1 Move for the rest of the game (minimum 1). Keep with the fighter |
| Shattered Armour | 2 | Armour 1 worse for the rest of the game (minimum 2+). Keep with the fighter |
| Bleeding Out | 2 | At the end of each round, the fighter loses 1 Wound. A Recover option discards this card instead of removing Fatigue |
| Decapitation | 1 | The fighter is taken out, whatever its Wounds. The attacker scores 1 Glory on top of the normal Glory for taking it out. Then shuffle all discarded Critical Injury cards, this one included, back into the deck |

Cards kept with a fighter are discarded when it is taken out. If the deck runs out, shuffle the discards to make a new one.
