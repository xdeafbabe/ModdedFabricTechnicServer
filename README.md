# Technic Fabric Server

Runs on Minecraft 1.18.1. Has some IndustrialCraft-like and BuildCraft-like things. Get Fabric loader from [FabricMC.net](https://fabricmc.net/), save it here as `server.jar` and run `./run` to start the server. You will have to accept the EULA after the first run by editing `eula.txt`. The server is configured for offline mode.

## Mods

Server requires clients to have [Fabric Loader](https://fabricmc.net/) and [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api).

### Installed server mods:
- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) —
  Required by most of Fabric mods.
- [AppleSkin](https://www.curseforge.com/minecraft/mc-mods/appleskin) —
  Shows saturation levels and changes along standard hunger HUD.
  Installed on server to provide more accurate information about saturation level.
- [Tech Reborn](https://www.curseforge.com/minecraft/mc-mods/techreborn) —
  General tech mod.
- [Quarry Reborn](https://www.curseforge.com/minecraft/mc-mods/quarry-reborn) —
  Adds quarries to Tech Reborn.
- [Simple BC Pipes](https://www.curseforge.com/minecraft/mc-mods/simplepipes) —
  Pipes and filters.
- [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) —
  Improves server performance.
- [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) —
  Improves chunk generation performance, reworking Minecraft lighting engine.
- [WTHIT](https://www.curseforge.com/minecraft/mc-mods/wthit) —
  Names blocks players are looking at and shows what mod they are from.
  Installed on server to provide extended information.
- [Megane](https://www.curseforge.com/minecraft/mc-mods/megane) —
  Mod support addon for WTHIT.
- [Can I mine this block?](https://www.curseforge.com/minecraft/mc-mods/can-i-mine-this-block) —
  Obtainability addon for WTHIT.
- [Inventory Sorter](https://www.curseforge.com/minecraft/mc-mods/inventory-sorting) —
  Sorts inventories.
  Does not work if not installed on server.
- [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton) —
  Increases server network stack performance.
- [Styled Player List](https://www.curseforge.com/minecraft/mc-mods/styled-player-list) —
  Customizes player list.
- [Styled Chat](https://www.curseforge.com/minecraft/mc-mods/styled-chat) —
  Customizes chat.
- [Skin Restorer](https://www.curseforge.com/minecraft/mc-mods/skinrestorer) —
  Fixes skins on offline servers.
- [EasyAuth](https://www.curseforge.com/minecraft/mc-mods/easyauth) —
  Adds authentication on offline servers.
- [ServerCore](https://www.curseforge.com/minecraft/mc-mods/servercore) —
  General performance tweaks for servers.
- [Ledger](https://www.curseforge.com/minecraft/mc-mods/ledger) —
  Block and container logging and rollback.
- [Fabric Language Kotlin](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin) —
  Required by Ledger.

### Required client mods:
- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) —
  Required by most of Fabric mods.
- [Tech Reborn](https://www.curseforge.com/minecraft/mc-mods/techreborn) —
  General tech mod.
- [Quarry Reborn](https://www.curseforge.com/minecraft/mc-mods/quarry-reborn) —
  Adds quarries to Tech Reborn.
- [Simple BC Pipes](https://www.curseforge.com/minecraft/mc-mods/simplepipes) —
  Pipes and filters.

### Recommended client mods for better server experience:
- [AppleSkin](https://www.curseforge.com/minecraft/mc-mods/appleskin) —
  Shows saturation levels and changes along standard hunger HUD.
- [Xaero's Minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap) —
  Minimap with additional HUD info.
- [Roughly Enough Items](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items) —
  Shows crafting recipes for mods.
- [Architectury API](https://www.curseforge.com/minecraft/mc-mods/architectury-fabric) —
  Required by Roughly Enough Items.
- [WTHIT](https://www.curseforge.com/minecraft/mc-mods/wthit) —
  Names blocks players are looking at and shows what mod they are from.
- [Megane](https://www.curseforge.com/minecraft/mc-mods/megane) —
  Mod support addon for WTHIT.
- [Can I mine this block?](https://www.curseforge.com/minecraft/mc-mods/can-i-mine-this-block) —
  Obtainability addon for WTHIT.
- [Farsight](https://www.curseforge.com/minecraft/mc-mods/farsight) —
  Prevents client from unloading chunks that are not loaded on server.
- [Inventory Sorter](https://www.curseforge.com/minecraft/mc-mods/inventory-sorting) —
  Sorts inventories.
- [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton) —
  Increases server network stack performance.

### Recommended client mods for all modes:
- [Mod Menu](https://www.curseforge.com/minecraft/mc-mods/modmenu) —
  Provides Fabric mods with a global menu.
- [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium) —
  Improves render engine performance.
- [Sodium Extra](https://www.curseforge.com/minecraft/mc-mods/sodium-extra) —
  Adds extra eye-candy things for Sodium.
- [Reese's Sodium Options](https://www.curseforge.com/minecraft/mc-mods/reeses-sodium-options) —
  Improves Sodium settings UI.
- [Indium](https://www.curseforge.com/minecraft/mc-mods/indium) —
  Adds compatibility layer for rendering mods and Sodium.
  Required by Iris and Continuity.
- [Iris](https://www.curseforge.com/minecraft/mc-mods/irisshaders) —
  Optifine shader support.
- [Continuity](https://www.curseforge.com/minecraft/mc-mods/continuity) —
  Connected textures like in Optifine.
- [Client Tweaks](https://www.curseforge.com/minecraft/mc-mods/client-tweaks-fabric) —
  Few minor gameplay tweaks.
- [Balm](https://www.curseforge.com/minecraft/mc-mods/balm-fabric) —
  Required by Client Tweaks.

### Recommended client mods for singleplayer:
- [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) —
  Improves server performance.
- [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) —
  Improves chunk generation performance, reworking Minecraft lighting engine.
