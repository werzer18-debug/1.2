# Corpse Run

> A roguelite where you can't win without dying — every time you die, your body
> stays and becomes part of the level.

## The hook
The exit is too high to reach alive. Death isn't a punishment — it's your only
tool. **Sacrifice** yourself and your corpse freezes in place as a solid
platform. Build a staircase out of your own dead bodies and climb out before you
run out of lives.

## Why it can stand
- **The hook *is* the gameplay** — no one frames death as the core resource.
- **Clippable** — a tower built of your own corpses is a screenshot that
  explains itself.
- **Buildable solo** — pure 2D, no netcode, no voice chat, no horror-atmosphere
  bar to clear.
- **Roguelite chassis** — procedural pits + run-based replay = cheap content,
  paying audience — but an original theme, so it's not a clone.

## Play the prototype
Open `index.html` in any browser. No install, no build step.

| Action | Keys |
|---|---|
| Move | `A`/`D` or `←`/`→` |
| Jump | `W` / `Space` / `↑` |
| Sacrifice (die in place) | `S` |
| Restart run | `R` |

## What this MVP proves
The single thing worth testing first: does a player look at the gap, realise
they have to *die on purpose* to cross it, and go *"ohhh"*? If yes, the hook is
real and everything after is content.

## Roadmap (after the hook lands)
- Procedurally generated shafts + escalating hazards (spikes, crushers, gaps).
- Corpse *types* — sacrifice mid-jump for a high platform, near a switch to hold
  it, in front of a hazard as a shield.
- Meta-progression between runs (the roguelite layer).
- Port to Godot for the full build + mobile/web export.
