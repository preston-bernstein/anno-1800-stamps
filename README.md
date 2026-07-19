# anno-1800-stamps

A personal collection of Anno 1800 city-planner "stamp" files — pre-built layout blueprints for production chains and public-service buildings, organized by region.

[![CI](https://github.com/preston-bernstein/anno-1800-stamps/actions/workflows/ci.yml/badge.svg)](https://github.com/preston-bernstein/anno-1800-stamps/actions/workflows/ci.yml)  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## What's a stamp

The stamp tool in Anno 1800 (via the City Planner / Stamps DLC feature) captures a placed arrangement of buildings, roads, and decorations as a reusable, exportable blueprint. Each file in this repo is one exported stamp — a compact binary snapshot of a specific building layout that can be re-imported into any save.

## Layout

```
The Old World/          # stamps built for the Old World region's terrain/module set
├── beef and red peppers
├── beer
├── canned meat
├── farmers town hall post office
├── investor
├── schnapps
├── simple bread
├── soap and sausage
├── super b city
├── timber production x4
├── work clothes
└── workers town hall post office
```

Each file is named for what it produces or houses (e.g. `beer`, `canned meat`) or the residence tier it serves (`investor`). Files have no extension — that's how the game exports them.

## Using a stamp

1. Copy the desired file into your Anno 1800 stamps folder, typically:
   - Windows: `Documents\Anno 1800\stamps\`
   - Ubisoft Connect / Steam installs use the same `Documents` path.
2. In-game, open the City Planner / Stamps menu and select the imported stamp.
3. Place it in your city like any other blueprint. Verify module/region compatibility — a stamp built for the Old World may not fit New World or Arctic terrain and modules.

## Format

Stamp files are zlib-compressed binary data (the game's native `.stamp` export format, stored here without the extension). They aren't meant to be opened or edited outside Anno 1800.

## License

MIT — see [LICENSE](LICENSE). The layouts are original designs; Anno 1800 and all in-game assets referenced by these blueprints are property of Ubisoft Blue Byte.
