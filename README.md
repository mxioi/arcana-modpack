# Arcana: Server Matched

![Minecraft 1.21.1](https://img.shields.io/badge/Minecraft-1.21.1-62B47A)
![NeoForge 21.1.248](https://img.shields.io/badge/NeoForge-21.1.248-orange)
![347 mods](https://img.shields.io/badge/mods-347-blue)
![Version 1.0.2](https://img.shields.io/badge/pack-1.0.2-informational)

A CurseForge modpack that matches the Arcana server's mod list exactly, so players can join without
"mismatched mod" errors or hunting down missing mods by hand.

## Install

**CurseForge app:** Create Custom Profile → **Import** → pick `Arcana-Server-Matched-1.0.2.zip`.

**Prism Launcher:** Add Instance → **Import** → pick the same zip.

Then launch once, and join with the server address the server owner gave you. No address is included here.

## What's in the repo

| Path | What it is |
|---|---|
| `Arcana-Server-Matched-1.0.2.zip` | The ready-to-import pack. Start here. |
| `manifest.json` | The full mod list (CurseForge project and file IDs), loader and Minecraft version |
| `overrides/` | Config files and KubeJS folder copied into the instance so settings match the server |

## Versions

| Version | Change |
|---|---|
| 1.0.2 | Added 13 client-only mods so the pack matches the full official client (347 mods) |
| 1.0.1 | Added Sodium (fixes a launch failure from a missing dependency) |
| 1.0.0 | First server-matched manifest |

## Keeping it in sync

When the server's mods change, update `manifest.json` and the configs in `overrides/`, bump the
`version` field, rebuild the zip from `manifest.json` and `overrides/`, and add a line to the table above.
