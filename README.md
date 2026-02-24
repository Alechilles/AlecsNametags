# Alec's Nametags!

A lightweight mod that adds a craftable nametag item for naming companions using Alec's Tamework.

## Features
- Adds `Alecs_Nametag`, a craftable naming tool.
- Uses Tamework's naming interaction (`TameworkNameNpc`).
- Default naming rules:
  - requires the NPC to be tamed
  - requires ownership, but also allows unowned tamed NPCs
  - allows renaming and replaces existing names
  - supports letters, numbers, and spaces

## Requirements
- Hytale server build: `2026.02.19-1A311A592`
- `Alechilles:Alec's Tamework!` `2.1.3`
- `Alechilles:Alec's Tamework! (Assets)` `2.1.3`

## Installation
1. Place this mod in your Hytale mods folder.
2. Ensure Alec's Tamework `2.1.3` is installed.
3. Start the server/client and craft `Alecs_Nametag`.

## Usage
1. Hold `Alecs_Nametag`.
2. Primary use on a valid NPC to name it.
3. Enter the desired name in the naming prompt.

## Asset Layout
- `Server/Item/Items/Naming/Alecs_Nametag.json`
- `Server/Tamework/Items/Naming/NameItem_Alecs_Nametag.json`
- `Server/Languages/en-US/server.lang`
- `manifest.json`
