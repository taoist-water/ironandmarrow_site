---
tags: [rules, board]
status: draft
source: Design doc, 26 Oct 2026 (rev 15)
---

# Arena and Deployment

The arena is a hexagon of 91 hexes (radius 5) with six deployment edges. That shape gives symmetrical seats at 2, 3 and 4 players, which a rectangular board cannot do at three.

| Players | Edges used | Layout |
| --- | --- | --- |
| 2 | 1 and 4 | Opposite edges |
| 3 | 1, 3 and 5 | Alternate edges |
| 4 | 1, 2, 4 and 5 | Two facing pairs |

In the 4-player layout every player has one adjacent rival, one at 120° and one directly opposite. No seat is better than another.

- **Deployment.** Fighters set up within 2 hexes of their own edge, one fighter at a time, in a random player order.
- **Objectives.** The centre hex, plus one objective hex 2 hexes in from each unoccupied edge. That gives 3 objectives at four players. Objective counts for 2 and 3 players still need testing.
- **Terrain.** Obstruction hexes block movement and line of sight. Pit hexes take out any fighter pushed into them. Layouts are still to be designed.
