<h1 align="center">Sterling Cast & Swing</h1>

A cast bar and swing timer for WoW Forever, for every class. Auto shot, wands, melee and dual wield, with the rules the Forever client actually follows.

> **A personal add-on.** I built this for my own needs and share it as is. Support will not be provided, and issues or feature requests may not be answered.

## What it does

**Swing timer**
- Hunters: the auto shot timer with the stand-still window at the end, a line where it starts, and a wait at the line while you move or cast
- Priests, mages and warlocks: the same timer for wand Shoot
- Everyone in melee: the melee swing timer while auto attack is on
- Dual wield: the bar splits, main hand on the top half, off-hand on the bottom half
- Queued next-swing attacks (Heroic Strike, Cleave, Raptor Strike, Maul) show their icon on the bar. Pick which ones from your spellbook
- A swing that comes due while you're casting is lost and the timer starts over, and finishing a cast restarts the swing, the way Forever does it
- Haste glow and "+30%" in the label while your swings are faster (Rapid Fire, Flurry, Slice and Dice, Berserking)
- Warnings, each with an optional sound: moving while aiming, a cast that delays your shot, out of range, the dead zone, a clipped shot, a failed shot or facing the wrong way

**Cast bar**
- Sits on top of the swing bar, same width, with the spell icon at the left
- Crafting shows the whole batch ("3 of 10")
- Latency zone at the end of a cast, pushback time when a hit delays you, and tick marks on channels (Volley, Blizzard, Drain Life, Mind Flay and more)
- Can hide the game's own cast bar

**Profiles**
- Settings are per character, or share the account-wide Default
- Make, copy and delete profiles by name, and pick which one new characters start on

## Settings

- **Swing:** melee timer, queued attacks and their picker, haste glow, dual wield split, casts restart the swing, global cooldown line, colors, warnings and sounds
- **Cast Bar:** show casts, hide the game's cast bar, icon, height, crafting batches, latency, pushback, channel ticks, colors
- **Bar:** unlock and drag (snaps to the center line, with a grid), size, when it shows, opacity in and out of combat, style presets, texture, edge, colors, and a test bar
- **Profiles:** pick, make, copy, reset and delete profiles, and the profile new characters start on

## Commands

| Command | What it does |
|---|---|
| `/stc` | Open or close the window |
| `/stc test` | Run the test bar |
| `/stc lock`, `/stc unlock` | Lock or unlock the bar for dragging |
| `/stc reset` | Move the window back to the middle of the screen |
| `/stc probe` | Record what the game reports for your swings and casts, then show it to copy |

## Install

Add this URL in WowUp: **Get Addons > Install from URL**

```
https://github.com/SterlingAddons/SterlingCast
```

Or download the zip from [Releases](https://github.com/SterlingAddons/SterlingCast/releases) and put the `SterlingCast` folder in `_forever_\Interface\AddOns`. Restart the game after a first install.

## License

MIT. See [LICENSE](LICENSE).

Built by Sterling with the help of Claude.
