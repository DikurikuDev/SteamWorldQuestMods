# (SAVE GAME) START WITH EVERYTHING (1.0)

A save game for game modding testing purposes, featuring:

- All 8 of each card, even those noncollectable;
- All heroes, with maxed-out level;
- All items, even those unobtainable;
- All consumables;
- All craft materials;
- All game features unlocked;

## Instructions

Uncompress all files using [SteamyWorld](https://github.com/DikurikuDev/SteamyWorld).

It's preferable to test at remix difficulty because monster cards may only appear at this difficulty. So, to show the remix as a choosable difficulty option, remove the `<NewGamePlusOnly>true</NewGamePlusOnly>` from remix difficulty at Definitions/difficulty.xml.

To unlock all the features, replace the new_game outset with [this](outsets.xml).

## Savegame locations

- Linux: ~/.local/share/SteamWorld Quest/
- Windows: Documents\My Games\SteamWorld Quest
