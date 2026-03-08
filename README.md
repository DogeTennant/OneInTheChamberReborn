# OneInTheChamberReborn

**One in the Chamber** is back! Feature-rich and reborn minigame plugin for Paper/Spigot 1.21+

> This repository contains documentation only. The plugin jar is available on... nowhere yet :(.

---

## Features

- **Multi-arena support** - run unlimited arenas simultaneously, each fully independent
- **Complete game loop** - lobby countdown, ready system, kill goal, time limit, and podium finish
- **Per-arena configuration** - override min/max players per arena without touching global settings
- **Player stats** - kills, deaths, wins, and K/D ratio tracked per player
- **Leaderboards** - top 10 for any stat type, queryable in-game or via placeholders
- **Rewards system** - configure item rewards and console command rewards for top 3 finishers via an in-game GUI
- **PlaceholderAPI support** - personal stats, leaderboard positions, and live arena data
- **MySQL support** - optional database backend with automatic migration from flat-file stats
- **Arena regions** - define arena and lobby regions to suppress mob spawning
- **Particle boundary visualizer** - see your region borders in-game
- **Interactive admin UI** - clickable chat buttons for teleportation, region management, and arena info
- **Kill feed broadcasts** - server-wide win announcements with per-player opt-out
- **Scoreboard** - live in-game scoreboard showing kills and time remaining
- **Multi-language** - English and Czech included, fully customizable message files
- **Console-compatible** - most admin commands work from the server console

---

## Requirements

| Requirement | Version |
|---|---|
| Paper / Spigot | 1.21+ |
| Java | 21+ |
| PlaceholderAPI | Optional |
| MySQL | Optional |

---

## Quick Start

1. Drop the jar into your `/plugins` folder and start your server
2. Run `/oitcr create <name>` to create an arena
3. Set a lobby spawn with `/oitcr setlobby <name>`
4. Add at least 4 spawn points with `/oitcr addspawn <name>`
5. You're ready - players can join with `/oitcr join <name>`

See the [full setup guide](../../wiki/Creating-your-first-arena) for all options including regions, per-arena limits, and admin teleport points.

---

## Documentation

Full documentation is available in the [Wiki](../../wiki):

- [Installation](../../wiki/Installation)
- [Creating Your First Arena](../../wiki/Creating-your-first-arena)
- [Commands & Permissions](../../wiki/Commands-and-Permissions)
- [Configuration Reference](../../wiki/Configuration-Reference)
- [MySQL Setup](../../wiki/MySQL-Setup)
- [PlaceholderAPI](../../wiki/PlaceholderAPI)
- [Rewards](../../wiki/Rewards)
- [FAQ & Troubleshooting](../../wiki/FAQ-and-Troubleshooting)

---

## Commands Overview

| Command | Description |
|---|---|
| `/oitcr join <arena>` | Join an arena lobby |
| `/oitcr leave` | Leave the current game or lobby |
| `/oitcr stats` | View your stats |
| `/oitcr stats <wins\|kills\|deaths\|kd>` | View leaderboard |
| `/oitcr arenas` | List available arenas |
| `/oitcr help` | Show all commands |

Admin commands require the `oitcr.admin` permission. See the [full command reference](../../wiki/Commands-and-Permissions).

---

## License

© 2026 DogeTennant. All rights reserved.

This plugin is a paid resource. You may not redistribute, decompile, modify, or resell this software in whole or in part without explicit written permission from the author.
