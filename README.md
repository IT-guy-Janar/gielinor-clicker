# Gielinor Clicker

An Old School RuneScape–themed idle clicker. Click monsters to deal damage, earn
gold, upgrade your gear, and push through repeatable areas — each ending in a boss.

## Play locally
Just open `index.html` in any browser. That's it — no build step, no dependencies.
Your progress saves automatically to the browser (localStorage).

## How it plays
- **Click** the monster to attack. ~10% of hits crit for triple damage (orange splat).
- **Gold** drops from every kill; bosses drop a lot more.
- **Weapons** set your base click damage (one-time tiered buys).
- **Strength** adds flat click damage and scales forever.
- **Familiars** deal automatic damage per second — buy many.
- **Perks** are global multipliers (click damage, gold find, familiar damage).
- Beat an area's **boss** (wave 10) to unlock the next area and raise that area's
  tier — higher tiers mean tougher monsters and bigger gold.

Adding a new area or weapon is easy: edit the `AREAS`, `WEAPONS`, or `FAMILIARS`
arrays near the top of the `<script>` block in `index.html`.
