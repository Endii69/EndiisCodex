# Endii's Codex

A profession guide addon for **WoW Forever**. Every recipe of every crafting profession: where to learn each pattern, and where to find each reagent.

Open it with `/codex` (or `/cg`), or click the book icon on the minimap.

## Features

- All recipes for Alchemy, Blacksmithing, Leatherworking, Engineering, Tailoring, Enchanting, Cooking and First Aid, including WoW Forever's own recipes.
- Where to learn each recipe: trainers, vendors, drops and quests, with map pins.
- Where to find each reagent: herbs, ore, fishing, monster drops and vendors.
- **Available in this zone**: recipes for your professions you can get where you are.
- **Reagents in this zone**: what your profession needs that you can gather or loot here.
- **Monster tooltips**: the patterns and reagents a monster can drop.
- **Vendor marks**: green (you can learn it), red (skill too low), blue (for an alt), check mark (already known).
- **Rising prices** (needs [Auctionator](https://www.curseforge.com/wow/addons/auctionator)): after a full auction house scan, the farmable items whose price rose the most, in tabs for gathering, monster drops and recipes. `/codex prices` shows the list again.
- Favorites, known recipes across your characters, and discoveries shared between players of the addon.

## Install

1. Go to [Releases](../../releases) and download the latest `EndiisCodex-vX.Y.zip`.
2. Extract it. You get a folder called `CraftGuide Forever`. Keep that name: WoW needs it.
3. Copy that folder to `World of Warcraft\_forever_\Interface\AddOns\`.
   The folder must sit directly in `AddOns` (not `AddOns\CraftGuide Forever\CraftGuide Forever`).
4. Start the game and type `/codex`.

Do not use the green "Code > Download ZIP" button: that folder has the wrong name and WoW will not load it.

## Data sources

See `CREDITS.md` inside the addon. Drop rates and positions come from Classic data and are rough figures.

## License

GPL-3.0, because the addon contains data derived from CMaNGOS classic-db (GPL-3.0).
