# Sapling 2.1.2 Quick Changelog

# General Changes
> - Updated to 1.21.60+

---

# Sapling 2.1.1 Changelog

## Sapling Features
> - `hopperCartTransfer` improvements.
>   - Now works when on rails.
>   - If the minecart is on a powered activator rail, item transfer will stop.

## Bug Fixes
> - Fixed an issue where `hopperCartTransfer` did not work in the Nether or The End.

---

# Sapling 2.1 Changelog

## General changes
> - `help` command has been reworked.
>   - Now shows descriptions for `commands` and `features`.
> - New `lang` system via `.lang` files.
>   - Translated to: `es_MX, es_ES, fr_FR, fr_CA, ja_JP, ko_KO, pt_BR, pt_PT, ru_RU, tr_TR & de_DE`
> - New `extensions` support
>   - Check our [extension example repository](https://github.com/SaplingDevs/Sapling-Extension-Example).

## Sapling Features
> - `pistonSpongeDrying` added in `server` module.
> - `hopperCartTransfer` added in `server` module.
> - `fullBright` added in `client` module.
> - `netherFogRemover` added in `client` module.

## Bug Fixes
> - `dispensableBlocks` does not dispense `gravel` & `dragon egg`.
> - Fakeplayer instance not works in old worlds.
> - `debugScreen` not shows `pale_garden` in biome section.
> - `Fakeplayer` instance stops working after joining world multiple times.

---

# Sapling 2.0.2 Changelog

## General
- Updated to `1.21.50`

## Bug Fixes
- Fixed `cauldronMud` and `cauldronConcrete` not working in the Nether and the End.
- Fixed `itemMagnet` not functioning with a full inventory.

---

# Sapling 2.0.1 Changelog

## Bug fixes
> - `./prof` shows more of 20 tps limit
> - `instamineEndstone` from `server` section not works
> - `instamineObsidian` and `instamineObsidian` in the `server` section are reversed

## Sapling Features
> - `infiniteTrades` added in `server` section
> - `debugScreen` improvements: 
>   - Now shows an XYZ crosshair when the player crouches.
>   - The chat is now visible while in the debug screen.
>   - Data and display now cycle at 1gt.

## Commands
> - `freecamera` added
> - `fc` (`#freecamera` shortcurt) added
> - `sc` (`#sapling client` shortcurt) added
> - `ss` (`#sapling server` shortcurt) added
> - `se` (`#sapling engine` shortcurt) added 


--- 

# Sapling 2.0 Changelog

# General changes:
> - Updated to 1.21.41+
> - Many optimization improvements.
> - Entire core rewrite.
> - New subcommands system.
> - Texture channels system
> - Now you require the tag `sapling_admin` to toggle server & engine features

# Sapling features
## Sapling `server` section
> - `dispensableBlocks` added
> - `instamineEndstone` added
> - `railDuping` added
> - `dispenserBadOmen` added
> - `oldPillagerMethod` added
> - `blazeMeal` added
> - `renewableDeepslate` added
> - `stoneCutterDamage` added
> - `simulatedHssViewer` added
> - `sweepingEdge` added
> - `cauldronConcrete` added
> - `cauldronMud` added
> - `phantomDisable` added
## Sapling `client` section
> - `itemMagnet` added
> - `smartHoe` added
> - `debugScreen` added
> - `collisionBoxes` added
> - `xpBarMending` added
> - `minecartStacking` added
> - `disableRendering` added
> - `toolChanger` extracted from `server-section`
> - `flippinCactus` extracted from `server-section`
> - `chunkBorders` extracted from `server-section`
> - `redstoneIndicator` extracted from `server-section`
## Sapling `engine` section
> - `simulatedHss` added
> - `javaMobCap` added
> - `gamerulesFix` extracted from `config-command`
> - `freeCamera` added

# Commands:
> - `#` prefix support
> - `fc` (freeCamera toggle) added (requires freeCamera engine enabled)
> - `gm` (gamemode changer) added 
> - `slimechunks` added
> - `materials` added
> - `fakeplayer` from `Fakeplayer Rework` added
> - `render` added (requires disableRendering enabled)
