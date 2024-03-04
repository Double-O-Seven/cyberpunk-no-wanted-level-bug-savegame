# Cyberpunk 2077 (v2.12) with Phantom Liberty - No wanted level bug

## Reproducible save game

`ManualSave-71` is a save game where I can reliably reproduce a bug where I no longer get any Wanted Levels for killing
civilians. In fact, it is impossible to aggro the cops in any way.

There seem to be some workarounds though:

* Walk through the scanner in Corpo Plaza apartment
* Use the CET mod to execute some command to fix the
  bug: https://www.reddit.com/r/cyberpunkgame/comments/16x3v40/bugfix_permanent_solution_for_broken_police/

The bug can be reproduced without any mods installed, although I did have a few mods installed when I discovered the
cause.

### Steps to reproduce the bug

1. Shoot _all 3 goons_ marked in the following image. Shooting only some of them doesn't seem to work.
2. After you've killed them all, turn around 180 degrees and find some civilians to kill. You will find out, that
   killing them will not give you any Wanted Level.

![Goons](./goons.png)