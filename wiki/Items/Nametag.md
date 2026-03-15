# Nametag

Parent: [Items Index](/mod/alecs-nametags/items) | [Home](/mod/alecs-nametags/readme)

The Nametag is the core item in Alec's Nametags. It opens a naming prompt for eligible companions.

## Crafting
- Crafting station: **Farmer's Workbench**
- Recipe:
  - 2x **Light Leather**
  - 1x **Gold Bar**
- Craft time: **1 second**
- Max stack: **1**

## How To Use
1. Hold a **Nametag**.
2. Left click a valid NPC.
3. Enter a name in the prompt.
4. Confirm to apply the name.

## Default Naming Rules
- NPC must be **tamed**.
- NPC must be **owned by you**, but unowned tamed NPCs are also allowed.
- Existing names can be replaced.
- Allowed characters: **letters, numbers, spaces**.
- Name length: **1 to 24 characters**.
- Leading/trailing whitespace is trimmed.
- Item is consumed on use.
- Reuse cooldown: **2 seconds**.

## Tips
- If nothing happens, verify the NPC is tamed and eligible under your current server config.
- Server owners can customize behavior in:
  - `Server/Tamework/Items/Naming/NameItem_Alecs_Nametag.json`

> [Screenshot Placeholder: Nametag recipe at Farmer's Workbench]
> [Screenshot Placeholder: Naming prompt UI]
