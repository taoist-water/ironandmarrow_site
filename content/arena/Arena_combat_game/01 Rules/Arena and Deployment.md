---
tags: [rules, board]
status: draft
source: Design doc v0.16
---

# Arena and Deployment

The arena is a hexagon of 91 hexes (radius 5) with six deployment edges. Each hex is 52 mm across the flats, so the board is about 510 × 572 mm, printed on 6 A3 sheets. That shape gives symmetrical seats at 2, 3 and 4 players, which a rectangular board cannot do at three.

![[Arena seating.png]]

In the 4-player layout every player has one adjacent rival, one at 120° and one directly opposite. No seat is better than another.

- **Deployment.** Fighters set up within 2 hexes of their own edge, one fighter at a time, in a random player order.
- **Objectives.** The number of objectives in play equals the number of players + 1, and the centre hex is always one of them. The others go on the six numbered perimeter hexes printed on the map, the second hex in from the middle of each edge. On an occupied edge that hex is inside the player's deployment zone. Objectives change each round; see the schedule below.
- **Terrain.** Obstruction hexes block movement and line of sight. Pit hexes take out any fighter pushed into them. Layouts are still to be designed.

**Objective schedule** (at the Prepare step of each round)

- **Round 1:** only the centre is an objective.
- **Round 2:** roll a d6 and place the perimeter objectives for your player count from the table below. Each set treats every seat the same, so nobody starts round 2 better placed.
- **Round 3:** the player with the lowest Glory chooses one perimeter objective to remove. If several players are tied lowest, they roll off and the highest roll chooses.
- **Round 4:** remove another the same way. The centre is never removed.

| Players | d6 roll | Perimeter objectives placed |
| --- | --- | --- |
| 2 | 1 or 4 | 1 and 4 |
| 2 | 2 or 5 | 2 and 5 |
| 2 | 3 or 6 | 3 and 6 |
| 3 | Odd | 1, 3 and 5 |
| 3 | Even | 2, 4 and 6 |
| 4 | No roll | 1, 2, 4 and 5 |

Letting the trailing player choose removals turns them into a catch-up tool: they will usually take away the objective nearest the leader.

| Players | Objectives in round 1 | Round 2 | Round 3 | Round 4 |
| --- | --- | --- | --- | --- |
| 2 | 1 | 3 | 2 | 1 |
| 3 | 1 | 4 | 3 | 2 |
| 4 | 1 | 5 | 4 | 3 |
