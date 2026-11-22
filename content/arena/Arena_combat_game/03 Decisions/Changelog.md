---
tags: [decisions]
status: draft
source: Design doc v0.16
---

# Changelog

Each revision is a git tag (v0.1, v0.2, …). To go back, ask Claude to restore or export a revision,
or run `git checkout v0.1 -- .` to bring back those files, then `git checkout main -- .` to return.

## v0.16 — 2026-11-01
From playtests 3 and 4 (a 2-player and the first 3-player game; Elite won both):
- +1 Wound to Leader and Duelist (4 to 5) and to Marksman and Skirmisher (3 to 4). Brute and Defender unchanged.
- Attacks-to-take-out target raised from 2–4 to 3–5. Tough now caps at 5 Wounds.
- Risks noted: Spite attacks picking the winner in 3–4 player games; Brute with Veteran (held for the next test).
- Creeds draft figures updated for the new Wounds.

## v0.15 — 2026-11-01
- New draft: Codex Fork, an optional deep-customisation layer that leaves the core rules untouched. Ranks (Lord,
  Heroes, Followers), equipment with weapon profiles, six skill tables, magic items in six categories, six spell
  lores with casting and dispelling, Creed access and relics, pricing anchors, an example 100-point warband.
- PDFs renamed with an underscore (e.g. "Arena Skirmish Game_Design Document.pdf"), matching TheTao's renames,
  so they upload cleanly; the Campaign Ideas PDF is no longer kept.

## v0.14 — 2026-10-30
TheTao's change, edited into the .docx and carried into the source:
- Basic Actions: Move (discard a card) is always available; Step, Guard and Draw only when your hand is empty.
- New Basic Action: Draw 1 Action card (empty hand only).
- Exhausted fighters may Step even with cards in hand, so they aren't frozen.

## v0.13 — 2026-10-30
- Page numbers: every document has a footer with its title and "Page X of Y" (added by md2docx.py, so future builds keep it).
- PDF copies of the four documents are now kept alongside the .docx files.

## v0.12 — 2026-10-30
- Creeds and Mounts drafts: Charge frequency corrected to 69% of hands (the deck has been 10 designs × 4 since v0.9).

## v0.11 — 2026-10-30
- Objective placement made fair: round 2 rolls a d6 for a seat-symmetric set (2P: rolled hex and its opposite;
  3P: odd 1-3-5 or even 2-4-6; 4P: 1, 2, 4 and 5).
- Rounds 3 and 4: the player with the lowest Glory chooses which perimeter objective is removed (ties roll off).
- Fatigue: no limit on tokens spent per attack (was 1 each side). No cap on Armour raised by Fatigue.

## v0.10 — 2026-10-30
- Last one standing wins at every player count (was 2 players only in v0.9).
- Objectives: players + 1, centre always in. Round 1 centre only; round 2 add the rest on the numbered
  perimeter hexes by d6; rounds 3 and 4 remove one perimeter objective each at random.
- Fatigue spends: each token spent can lower the target's Armour, remove an attacker's die, raise the target's
  Armour against a Fatigued attacker, or cut 1 hex from a Fatigued fighter's move (any number per move).
  The attacker spends first.
- 52 mm map legend updated for the perimeter objectives.

## v0.9 — 2026-10-30
From playtest 2 (2 games, 2 players, the example warbands), rules decided during play:
- Last one standing wins at once, whatever the Glory (2-player games; 3–4 players still use Fate of the Slain, pending confirmation).
- Critical Injuries trigger on one uncancelled natural 6; saves cancel the lowest hits first. 35% of 3-dice attacks now crit (was 3.4%).
- New Critical Injury: Decapitation (1 copy): taken out whatever its Wounds, +1 Glory, then reshuffle all discards. Deck now 13 cards.
- Taunt is a Reaction costing 1 Wrath: redirects an attack to another of your fighters.
- "Fury" retired: Wrath options and Wrath Strike. Bloodied Fury renamed Berserk; its Wrath Strike is now −2 Wrath: +3 dice (the "crits on 5+" would have critted 85% of the time).
- New Action cards Vendetta (Defiance: +1 Wrath) and Blood Oath (Bleed: lose 1 Wound, +2 Wrath); both only for a player behind on Glory. Deck is now 10 designs × 4.
- Riposte gives the riposting fighter 1 Fatigue.
- The design doc's .md is now the source; its .docx is built from it, diagrams included.

## v0.8 — 2026-10-28
- Turning is free while moving (reverses the v0.6 cost of 1 hex). Turning without moving still needs a "turn" option.
- Playtest check replaced: count rear-arc attacks per game to see whether facing still matters.
- Creeds draft: Elven Grace keeps +1 hex on every move; its free-turning clause is gone, since everyone turns free.

## v0.7 — 2026-10-28
- Wrath spends any warband can use: Rage (1: +1 Attack die), Shake Off (1: remove 1 Fatigue),
  Seize (2: activate a fighter before the drawn Initiative card's owner, once per round).
- Wrath can't be spent below 2 (closes a loophole: Initiative never drops below 2 cards).
- Reactions defined: no activation, no Fatigue, can't be reacted to. Riposte needs the attacker in the
  defender's Kill Zone, so rear-arc attacks can't be Riposted.
- New Wrath cards, one per player colour: a 2–8 track and the three spends. Riposte card text clarified.

## v0.6 — 2026-10-28
From playtest 1 (2 rounds, 2 players): a tank on an objective was never moved, and the cards' fixed
Move values ignored the Move stat.
- Movement is a Basic Action: discard any card to move up to the fighter's Move. Step (1 hex) and Guard need no card.
- No card has a plain Move option any more. Freed slots: Charge (Advance), Shove (Brutal Swing),
  Harry (Sweep), Scheme: draw 2 (Sidestep, Opportunist), War Cry (Bloodied Fury).
- Charge: move up to half Move (round up), then Strike, +1 Fatigue.
- Shove: push 1 hex directly away; if blocked, the target gains 1 Fatigue instead.
- Turning costs 1 hex of movement; "Turn, then Strike" still turns for free.
- Shove, Charge and Fatigue-giving options each come up in 78% of hands (Shove was 51%).
- Card sheets rebuilt. Creeds (Elven Grace, Beastkin maths) and Mounts drafts updated to match.

## v0.5 — 2026-10-27
- Creeds draft, wave 2: Orc Warhost, Goblin Rabble, Beastkin Herd, Vampire Court, Dwarf Hold,
  Elven Wardens, Infernal Host. Each has a Creed rule, restriction, 3 exclusive traits and a 60-point list.
- New draft: Mounts as a fourth trait category (Warhorse, Great Wolf, War Boar, Demon Beast, Winged Beast),
  with Creed access, a Move cap of 6 and a 50 mm base limit.
- Draft .docx tables no longer break words mid-column.

## v0.4 — 2026-10-27
- Hex size set to 52 mm across the flats (rules: Arena and deployment). Board about 510 × 572 mm.
- New print map: 52 mm hexes on 6 A3 landscape sheets (2 across × 3 down); seams avoid every objective hex.
- The 36 mm and 44 mm maps are superseded; they stay in the folder and in history.
- Still pending: Footprint rule (52 mm hexes fit bases up to 48 mm with 2 mm clearance, 50 mm snug);
  4-player corner deployment hexes; edge objective placement; Critical Injury and Arena Challenge lists;
  Shove and "crits on 5+" card wording; Creeds.

## v0.3 — 2026-10-27
- New draft: Creeds (6 warband identities, each with a Creed rule, restriction, Sorcery access,
  3 exclusive traits and a ready-made 60-point list). Not in the rules yet.
- New draft: Campaign Ideas (the Circuit, progression, injury, economy, fairness, hooks to protect now).
- Tools: md2docx.py builds the draft .docx files from Markdown using the design doc's styles.

## v0.2 — 2026-10-27
- Setting fixed as grimdark sword-and-sorcery fantasy; pillar 3 is now "Any models, one setting".
- Warband builder: 60 points (all costs ×5); traits in three categories (Gear, Skills, Sorcery);
  Sorcery used by Channelling (discard an Action card); Heavy Armour left out; Tough capped at 4 Wounds.
- Print maps: 36 mm hexes (2 × A3) and 44 mm hexes (4 × A3).
- Card sheets, first draft: Action, Initiative, Critical Injury (draft), Arena Challenge (draft), Fighter cards, backs.
- Pending, not yet in the rules: hex size and 1-hex footprint; 4-player corner deployment hexes;
  edge objective placement; Critical Injury and Arena Challenge lists; Shove and "crits on 5+" card wording.

## v0.1 — 2026-10-26
- Design document as first imported (concept, pillars, round structure, Wrath, Action cards,
  combat, Fatigue, arena, chassis + traits at 12 points, scoring, open questions).
