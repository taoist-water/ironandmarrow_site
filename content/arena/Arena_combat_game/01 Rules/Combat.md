---
tags: [rules, combat]
status: draft
source: Design doc, 26 Oct 2026 (rev 15)
---

# Combat

Combat is SAGA's two-roll structure applied to individual fighters: roll to hit against the target's Armour, then the target rolls flat saves. Each uncancelled hit removes 1 Wound. All dice are d6.

1. **Target.** The target must be in the attacker's Kill Zone. The default melee Kill Zone is the 3 hexes in the fighter's front arc. Ranged fighters use their range in hexes, within the front arc and line of sight.
2. **Hit.** Roll the attacker's Attack dice. Each die equal to or above the target's Armour is a hit. A natural 6 always hits; a natural 1 always misses.
3. **Save.** The target rolls one die per hit. Each 5+ cancels a hit. A Guarded fighter, or one in cover against ranged attacks, saves on 4+. An attack from the target's rear arc means it saves only on 6.
4. **Damage.** Each uncancelled hit removes 1 Wound. If two or more uncancelled hits were natural 6s, the target also draws a Critical Injury card.
5. **Whiff.** If no dice hit, the attacker's warband gains 1 [[Wrath]].

Armour is the stat that matters most, so the save threshold stays flat and changes only with the situation (Guard, cover, rear arc). Facing sets each fighter's 3-hex front arc and 3-hex rear arc. A fighter turns as part of any Move.

## Expected damage from a 3-dice attack

Expected damage = dice × P(hit) × P(save fails).

| Target Armour | Normal (save 5+) | Guarded (save 4+) | From rear (save 6) |
| --- | --- | --- | --- |
| 3+ | 1.33 | 1.00 | 1.67 |
| 4+ | 1.00 | 0.75 | 1.25 |
| 5+ | 0.67 | 0.50 | 0.83 |

Against Armour 4+ and 3–5 Wounds, a fighter goes down to 3–5 normal attacks, or 2–4 from the rear. The top of that range is slower than the 2–4 attack target, so 5-Wound fighters should be rare and expensive. Armour 5+ halves incoming damage compared to 3+, so it needs to be priced heavily. A 3-dice attack against Armour 4+ whiffs 12.5% of the time; against Armour 5+, 30%.
