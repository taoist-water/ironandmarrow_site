---
tags: [playtest, risks]
status: draft
source: Design doc v0.16
---

# Playtest Plan

The biggest risk is speed. Two rolls per attack, four players and a shared deck could push the game well past 75 minutes, so the first tests should measure time.

**Playtest 1 (28 Oct, 2 rounds, 2 players).** A tank sat on an objective and was never moved: Shove was only on Sweep (5 of 40 cards). The cards' fixed Move values ignored the Move stat, so Swift and fast chassis did nothing. Both are addressed in v0.6.

**Playtest 2 (30 Oct, 2 games, 2 players, the example warbands).** Game 1 ended in round 3 when the Wide warband wiped out the Elite one. Game 2 went 4 rounds; Elite won by 1 Glory. Rules decided during play, now in v0.9: last one standing wins; Critical Injuries on a single uncancelled 6 with lowest hits cancelled first; Decapitation; Taunt as a Reaction costing 1 Wrath; Fury renamed Wrath; Wrath-gaining cards; Riposte gives 1 Fatigue.

**Playtests 3 and 4 (1 Nov, 4 rounds each).** A 2-player game went to the Elite warband by 1 Glory. The first 3-player game also went to Elite, 9–8–5; one warband was wiped out in round 4 and still took out a fighter with a Spite attack. Fighters other than the Brute died very quickly, and Veteran on a Brute stood out. Elite has now won 3 of the last 4 games. Measured: a Leader took 3.9 attacks to take out from a 3-dice attacker, but 2.2 from a Brute with Veteran when 1 Fatigue was spent per attack. v0.16 adds 1 Wound to Leader, Duelist, Marksman and Skirmisher.

**Known risks**

- **Dogpiling the leader.** The Bounty may push three players onto one warband every round. Watch whether the leader can ever hold a lead.
- **Activations per player are fixed by Wrath.** A 4-fighter warband may feel like it never gets to use everyone. If so, scale base Wrath with fighter count.
- **Wrath timing.** A Wrath point spent in round 1 costs 3 activations; in round 4 it costs nothing. Expect players to hoard Wrath early and dump it in round 4. Watch whether that round 4 dump decides games.
- **Fate of the Slain power.** Spite actions must matter enough to keep the player engaged, without letting them decide the winner.
- **Armour 5+ Defenders** may make objectives impossible to contest.
- **Sorcery combos.** Compel plus Blink sets up a rear-arc Backstab (+2 dice, target saves only on 6). If that decides games, raise Compel's cost.
- **Critical Injuries are now common.** 35% of 3-dice attacks cause one, so fighters weaken fast and games get shorter. Backstabber (2 points) now lifts a rear 3-dice attack from 39% to 65%, and a Backstab with it to 84%: it is underpriced.
- **Decapitation swings games.** With 1 card in 13, a game with 8 Critical Injuries sees at least one Decapitation about 47% of the time: 2 Glory plus a lost fighter, in games decided by 1 Glory.
- **Last one standing at 3–4 players.** Wiping out a warband now ends the game if it is the last rival, which rewards killing the weakest warband. That pulls against the Bounty, which rewards hitting the leader.
- **Objective removal is a choice.** With 3–4 players, the trailing player decides whose nearby objective disappears, which is a kingmaking decision between rivals. Placement is fair: fully random placement had left one player with up to 2.9 more uncontested objective-rounds than another.
- **Fatigue can push Armour to 6+, by choice.** A Defender (Armour 5+) raised to 6+ takes 0.33 damage from a 3-dice attack, which makes objective-camping worse.
- **Fatigue spends stack.** With no limit per attack, 2 tokens take Armour 4+ to 2+ and lift a 3-dice attack from 1.00 to 1.67 damage. A third token adds nothing, because a natural 1 always misses.
- **Spite can pick the winner.** In the 3-player game, a wiped-out warband's Spite attack took out a fighter in a game decided by 1 Glory (9–8). The slain player chooses whom to hurt, which is kingmaking.
- **Brute with Veteran.** The most efficient killer in the game: a Brute takes out a 4-Wound Leader in 3.0 attacks, 2.7 with Veteran. Left as it is for one more test, so the Wounds change can be judged alone.
- **Wrath gain lengthens games.** Each extra Wrath point is one more activation per round. Defiance and Bleed only work for trailing players, which keeps the inflation to them.

**First playtests**

- [ ] Combat only, 2 players, no cards: do fighters fall in 3–5 attacks?
- [ ] Full game, 2 players: time per round, and how often Fatigue gets spent.
- [ ] Full game, 4 players: total time under 75 minutes? How often does a player go 6 or more Initiative draws without a turn?
- [ ] Record final Glory spread: is the last-place player within 3 Glory of first?
- [ ] After v0.6 movement: count Shoves per round. At least 1 per player per round means objective holders can be moved.
- [ ] After v0.6 movement: is a fighter sitting on an objective ever moved or Exhausted off it within 2 rounds?
- [ ] After v0.8: with free turning, fighters can end every move facing the threat. Count rear-arc attacks per game; near zero means facing has stopped mattering.
- [ ] After v0.7: record every Wrath spend and its round. Spends only in round 4 mean early spends are priced too high.
- [ ] After v0.7: count Seizes per game, and who used them. If the Glory leader Seizes most, Seize should cost 3.
- [ ] Calculation: attacks to take out for every legal chassis and trait combination. Anything above 5.0 other than the Defender is mispriced or should be banned.
- [ ] Full game, 2 players, the two example warbands: how often is Sorcery Channelled? Never means the card cost is too steep; every activation means it is too cheap.
- [ ] After v0.9: count Critical Injuries and Decapitations per game, and note whether a Decapitation decided the result.
- [ ] After v0.9: record each player's Wrath at the start of every round and the game's length. Rising totals and longer games mean Defiance and Bleed are too strong.
- [ ] After v0.10: record how many games end by last one standing, at each player count and in which round.
- [ ] After v0.11: record who removed which objective in rounds 3 and 4, and whose objective it was. If removals always target the leader, the catch-up works; if they target a rival of the remover, it is kingmaking.
- [ ] After v0.11: record the most Fatigue tokens spent on a single attack.
- [ ] After v0.16: count attacks per fighter taken out, by chassis. Target 3–5. Record which warband won (Elite has won 3 of the last 4).
- [ ] After v0.14: count Guards per game, and how often a player had an empty hand. Far fewer Guards should mean faster, more aggressive games.
- [ ] After v0.10: count Fatigue spends by type (Armour down, die removed, Armour up, movement).
