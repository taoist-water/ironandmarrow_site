---
tags: [rules, core-loop]
status: draft
source: Design doc v0.16
---

# Round Structure

The game lasts 4 rounds. Turn order each round comes from a shuffled Initiative deck, built from every player's Wrath, so nobody knows who acts next.

1. **Prepare.** Each player may keep 1 Action card from last round, then draws up to a hand of 5. Each player puts Initiative cards into the deck equal to their current Wrath (minimum 2, maximum 8). Shuffle.
2. **Fight.** Turn over the top Initiative card. Its owner activates one fighter: play an Action card and resolve one of its options, or take a Basic Action. Repeat until the deck is empty.
3. **End.** Score Glory, adjust Wrath, each fighter removes 1 Fatigue, Guard tokens are cleared.

![[Round flow.png]]

Activations belong to the player, not the fighter. A player with Wrath 4 gets 4 activations whether they field 3 fighters or 4. A small elite warband spends its activations on fewer fighters and piles up Fatigue faster. A wide warband spreads them out. That is the main warband-building trade-off.

**Basic Actions**

Instead of resolving a card option, the activated fighter can take one Basic Action. Move is always available; Step, Guard and Draw only when your hand is empty.

- **Move:** discard any Action card, then move up to the fighter's Move in hexes.
- **Step (empty hand only):** move 1 hex.
- **Guard (empty hand only):** the fighter gains a Guard token.
- **Draw (empty hand only):** draw 1 Action card.

Move and Charge are the only ways to cover ground, so a fighter's Move stat matters and any card can be spent on movement. Step, Guard and Draw exist so an empty hand never means a dead turn. While you hold cards, every activation spends one, which keeps each choice costly. Guard is still on 12 of the 40 cards (Advance, Hold the Line and Vendetta), so a 5-card hand holds it 85% of the time.
