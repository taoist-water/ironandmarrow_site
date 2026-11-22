---
tags: [draft]
status: draft
source: Design doc v0.16
---

# Mounts (draft)

Oct 27, 2026 · @TheTao · *Draft for review. Nothing here is in the rules yet.*

## Why mounts, and what they cost the rules

**What it solves:** players own mounted miniatures and have no rules to field them, which works against pillar 3. **What it replaces:** nothing. It adds a fourth trait category, not a new subsystem.

That only works because of the 52 mm hexes. A horse or wolf on a 25 × 50 mm or 50 mm base fits inside one hex, so a mounted fighter moves, turns and fights exactly like any other fighter. Bigger mounts would need rules for models that cover several hexes, and the rules don't have those yet.

## How mounts work

- A Mount is a trait. It counts toward the 2-trait limit, so a mounted fighter has one other trait at most.
- A fighter can have only one Mount.
- A Defender cannot be mounted.
- The mounted model's base must be 50 mm or smaller. This depends on raising the 1-hex footprint limit from about 40 mm to 50 mm, which is still pending.
- No fighter's Move can go above 6, whatever its traits.
- Each Creed lists which Mounts it can take (table below).

## Mount list

| Mount | Cost | Effect |
| --- | --- | --- |
| Warhorse | 7 | +2 Move. Charges roll +1 die |
| Great Wolf | 6 | +1 Move. After this fighter Strikes, it may move 1 hex |
| War Boar | 6 | +1 Move. Charges roll +2 dice |
| Demon Beast | 6 | +1 Move. The first melee attack against this fighter each round rolls 1 fewer die |
| Winged Beast | 8 | +2 Move. Ignores Obstruction and Pit hexes while moving |

**Pricing:** each Mount is built from existing prices. Swift (+1 Move) costs 3, so +2 Move is worth 6. A move after Striking is Blade-dance (3), and the first-attack penalty is Horrific (3). A Charge bonus comes up often: Advance and Lunge both offer a Charge (8 of the 40 cards), so a 5-card hand holds at least one 69% of the time. A Charge covers half the fighter's Move, so +2 Move also adds 1 hex of Charge reach.

## Mount access by Creed

| Creed | Mounts |
| --- | --- |
| Witch-Hunters | Warhorse |
| Rift Cult | Demon Beast |
| The Unburied | Warhorse (skeletal steeds) |
| Free Company | Warhorse |
| The Penitent | None |
| Gutter Kin | None |
| Orc Warhost | War Boar |
| Goblin Rabble | Great Wolf |
| Beastkin Herd | None |
| Vampire Court | Warhorse, Winged Beast |
| Dwarf Hold | None |
| Elven Wardens | Warhorse |
| Infernal Host | Demon Beast |

## Maths: speed on a small board

The arena is 11 hexes across, and the centre is about 4–5 hexes from any deployment zone. Move 4 already reaches the centre in one activation. Mounts mostly buy reach to rear arcs and far objectives, not raw speed:

- An attack from the rear deals 1.25 damage instead of 1.00 (3 dice against Armour 4+, save 6 instead of 5).
- A Backstab from the rear adds +2 dice on top.
- Without the Move cap, a Skirmisher with Swift and a Warhorse would have Move 8, enough to cross most of the board in one activation. The cap of 6 stops that.

## Risks

- **Rear-arc access.** A Move 6 fighter can reach almost any rear arc on the board. If mounted fighters win most Backstabs, the cap should drop to 5.
- **Bigger mounts.** Ogres, monsters and chariots on bases over 50 mm need rules for models covering several hexes. That is a separate piece of work, not part of this draft.
- **Charge strength.** Charge is on two card designs (69% of hands). If Warhorse and War Boar riders dominate melee, their Charge bonus should drop by 1 die.

## Playtest checks

- [ ] 2-player game, one mounted warband against one unmounted: count objective Glory per round for each side.
- [ ] Count how often a mounted fighter gets a rear-arc attack, compared with an unmounted one.
- [ ] Record how often Warhorse and War Boar riders actually Charge.

## Decisions needed

1. Adopt Mounts as a fourth trait category.
2. Raise the 1-hex footprint limit to 50 mm bases, which Mounts depend on.
3. The Move cap of 6.
4. Approve, change or cut each Mount and the access table.
