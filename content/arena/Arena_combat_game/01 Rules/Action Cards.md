---
tags: [rules, cards]
status: draft
source: Design doc v0.16
---

# Action Cards

All players draw from one shared, faction-neutral deck of 40 cards: 10 designs, 4 copies each. Each card offers three options, and you resolve one. Warband identity comes from fighter traits, not cards, which keeps the game miniature-agnostic.

**Reactions**

A Reaction is played when its trigger happens, usually during another player's activation. It does not use an activation. Riposte and Taunt are the Reactions on the Action cards.

- **Riposte:** when an enemy attacks one of your fighters in melee, you may discard a card showing Riposte. After the attack resolves, if your fighter is still standing and the attacker is in its Kill Zone, it Strikes the attacker with 1 fewer die. Then your fighter gains 1 Fatigue.
- **Taunt:** when an enemy declares an attack on one of your fighters, you may discard a card showing Taunt and spend 1 Wrath. If another of your fighters is a legal target for that attack, the attack targets it instead.
- The whole card is discarded; its other options are lost.
- A Reaction can't trigger another Reaction, so a Riposte can't be Riposted.
- Because the attacker must be in the defender's Kill Zone, an attack from the rear arc can't be Riposted.

**Starter list (first draft)**

| Card | Option 1 | Option 2 | Option 3 |
| --- | --- | --- | --- |
| Advance | Charge | Strike | Guard |
| Lunge | Charge | Precise Strike (re-roll misses) | Riposte |
| Brutal Swing | Shove | Heavy Strike (+1 die) | Wrath Strike (−1 Wrath: +2 dice) |
| Sweep | Harry | Cleave (every enemy in front arc, −1 die each) | Shove |
| Sidestep | Scheme | Turn, then Strike | Riposte |
| Hold the Line | Guard | Strike | Recover (remove 1 Fatigue) |
| Berserk | War Cry | Taunt (Reaction, −1 Wrath) | Wrath Strike (−2 Wrath: +3 dice) |
| Opportunist | Scheme | Backstab (rear arc only, +2 dice) | Recover |
| Vendetta | Defiance (+1 Wrath) | Precise Strike (re-roll misses) | Guard |
| Blood Oath | Bleed (+2 Wrath) | Heavy Strike (+1 die) | Harry |

No card has a plain Move option: movement is a Basic Action. Strike uses the fighter's own Attack dice. Every card with a Wrath option also offers options that don't involve Wrath, so a player low on Wrath still has a usable card.

- **Charge:** move up to half the fighter's Move (round up), then Strike. The fighter gains 1 Fatigue.
- **Shove:** push an enemy in the Kill Zone 1 hex directly away from this fighter. If that hex is blocked by a fighter, an Obstruction or the board edge, the enemy gains 1 Fatigue instead. A fighter Shoved into a Pit is taken out.
- **Harry:** an enemy in the Kill Zone gains 1 Fatigue.
- **War Cry:** every enemy adjacent to this fighter gains 1 Fatigue.
- **Scheme:** draw 2 Action cards. Cards still above 1 are discarded at the next Prepare step, so they can't be hoarded.
- **Defiance:** if any opponent has more Glory than you, gain 1 Wrath.
- **Bleed:** if any opponent has more Glory than you, this fighter loses 1 Wound and you gain 2 Wrath.
- **Wrath options** are the options that cost or gain Wrath: Wrath Strike, Taunt, Defiance and Bleed.

**How often each option comes up.** With 4 copies of each design, an option on two designs is on 8 of the 40 cards, so a 5-card hand holds at least one 69% of the time; an option on one design, 43%. Charge, Shove, Scheme, Riposte, Recover, Wrath Strike and Wrath gain (Defiance or Bleed) are each at 69%. Fatigue-giving (Harry on two designs, War Cry on one) is at 85%. Moving from 8 designs to 10 cost Shove some frequency: it was 78%.
