# OSRS Tick Trainer

Browser drills for practising tick-perfect attack timing against OSRS bosses. Open `index.html` in any browser; there's no build step.

## Leviathan (first boss)

- 13×13 tile arena, 600 ms game ticks (slow modes at 900/1200 ms).
- Click a tile to move (you run 2 tiles per tick, straight-line steps). Click the Leviathan to attack.
- Your weapon cooldown keeps counting down while you move, so dodge on cooldown ticks and re-click the boss to keep your cadence.
- Falling debris shows a shadow with a tick countdown. Be off the tile when it reaches 0.
- Debris speeds up below 66% and 33% HP; each threshold stuns the boss for 8 ticks (+25% damage, no debris).
- The tick strip shows each tick: attack, moved on a cooldown tick, waiting, or lost tick (weapon ready but no attack).

Simplifications: no prayers yet (boss volleys are visual only), simplified pathing, approximate weapon stats.
