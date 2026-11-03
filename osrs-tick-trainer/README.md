# OSRS Tick Trainer

Browser drills for practising tick-perfect play against OSRS bosses. Open `index.html` in any browser; there's no build step.

## Leviathan

Runs on fixed 0.6 s game ticks. Clicks are queued and resolved on the next tick, the last click in a tick wins, and you run 2 tiles per tick.

- **Arena:** the Leviathan sits in a central pool; you move on the ring around it.
- **Volleys:** orbs every 4 ticks (3 below 50%, 2 when enraged) while rocks fall on you. Shadows count down in ticks.
- **Stun:** select Shadow Barrage (F) and click the boss. Stuns for 15 ticks; attack the wound on its back (north side) for boosted damage. If a volley ends without a stun, boulders drop in a plus shape on you.
- **Specials:** after each stun, alternating:
  - *Lightning:* a current chases you 1 tile/tick (3 tiles per 2 ticks when enraged). You run 2, so each attack tick costs a tile of lead.
  - *Smoke blast:* debris lands around you and stays; stand with a rock between you and the boss before the blast.
- **Enrage at 180 HP:** 2-tick orbs and the abyssal pathfinder. Outside its 5x5 area, orbs hit you; inside, your accuracy goes up.
- **Modes:** full fight, short fight, enrage only, and lightning drills (normal and enraged).

Not exact: prayers aren't included (orbs assume perfect prayer outside enrage), and special durations, damage and lightning behaviour are approximations.
