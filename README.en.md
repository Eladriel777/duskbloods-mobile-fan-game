# The Duskbloods · Mobile Fan Game

[简体中文](README.md) | [English](README.en.md)

Finished playable editions in Chinese and English.

**Mobile touchscreen only, in landscape mode. Desktop keyboard and mouse play is not supported.**

A single-player action game for phones: choose one of six characters, fight across nine regions, collect upgrades, summon a familiar, and prepare through three growth phases before facing the final boss.

**This is an unofficial fan game.** Character names and the setting reference The Duskbloods. This project is not affiliated with the original rights holders. Visuals and sound effects are generated procedurally; no official artwork or audio asset files are included.

## Open the game

| Language | Game file |
| --- | --- |
| Chinese | [index.html](index.html) |
| English | [en/index.html](en/index.html) |

Each HTML file contains the complete game and the Phaser 3.90.0 engine. It does not rely on a CDN, external assets, or server APIs. Upload the finished file to a static web host, then open the game URL in a phone browser. GitHub's file viewer displays the source code; it does not run the game.

Use an HTTP(S) link and hold your phone in landscape orientation. Opening a local HTML file through a file manager depends on the phone's operating system. The first tap attempts to enter fullscreen and enable sound; fullscreen availability depends on the browser.

This repository contains the finished Chinese and English games, usage documentation, and licenses. Development logs, patch scripts, test recordings, browser profiles, and earlier versions are excluded.

## Touch controls

Hold the left side of the screen to move. Use the buttons at the bottom right for melee attacks, ranged attacks, dodging, draining blood, howling, and Blood Arts. The game automatically aims at the nearest enemy. A rotation prompt appears in portrait orientation.

Attack enemies to build up stagger, then drain a staggered target to deal damage and recover health. Howling can interrupt enemy wind-ups and knock down projectiles.

## Gameplay

- **Six characters:** Albert, "Bloodhand" Jan, Trang Lanh, Sniper Layla, Senator Samir Patres, and Zork. Each has different weapons and Blood Arts.
- **Four phases:** the first three last 60 seconds each and focus on fighting and growth. Phase transitions relocate you, restore health, and refresh enemies. The fourth phase is the battle against Bloodstained Volvad.
- **Nine regions:** Usanea Cathedral, City Streets, Liti Great Bridge, Sewers, Central District, Styx Lake, Heretic Forest, Underground Ruins, and Clock Tower.
- **Progression:** forge furnaces upgrade weapons; three-choice upgrades and Bloodfeasts provide additional growth. The player can reach level 20.
- **Familiars:** summon a Twinblade or Flame Mage familiar. Choose one type per run; familiars can reach level 5.

## License and credits

Original code is licensed under [MIT](LICENSE), with copyright credited to Eladriel777. Implementation was developed with assistance from AI coding tools. The bundled Phaser 3.90.0 engine is distributed under its own [MIT license](licenses/Phaser-MIT.txt).

Rights to the original game's characters, names, marks, and setting remain with their respective rights holders. The MIT code license does not grant rights to those elements. See [NOTICE.md](NOTICE.md) for source and attribution details.
