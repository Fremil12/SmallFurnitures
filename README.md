# This mod includes smaller Furniture.
## Caution
*This mod probably throws the balance of Ostranauts out of the window. This mod could be used to make prettier, smaller ships.*

## Furniture included in this mod:
- 2x6 Comfortable Bed
## Furniture planned:
- 1x1+3 Cooler
- 2x1 Heater

Source: ([github](https://github.com/Fremil12/SmallFurnitures))

## Versions:
- [1.0.8](https://github.com/Fremil12/SmallFurnitures/releases/tag/v1.0.8)  (First working version)
- [2.0.8](https://github.com/Fremil12/SmallFurnitures/releases/tag/v2.0.8)  (FFU-BR dependency)

## Installation guide for 1.0.8
### Other mods that change loot.json is incompatible, use 2.0.8+
1. Put the mod into `Ostranauts\Ostranauts_Data\Mods`
2. Make sure that in `loading_order` put the mod at the bottom of the load order (below anything that changes the loot.json (which isnt compatible with FFU-BR)
## Installation guide for 2.0.8+
1. Download BepInEx v5.4.23.2 WINx64: https://github.com/BepInEx/BepInEx/releases/tag/v5.4.23.2
2. Unzip all contents into `Ostranauts` root folder. It should contain now `BepInEx`, `winhttp.dll` & etc.
3. Download MonoMod Loader: https://github.com/BepInEx/BepInEx.MonoMod.Loader/releases/tag/v1.0.0.0
4. Unzip all contents into `Ostranauts` root folder. `Ostranauts/BepInEx/core` should now contain `MonoMod.dll`.
5. Download [Fight for Universe: Beyond Reach dll file](https://github.com/WarStalkeR/FFU-BR/releases/tag/v0.3.4.0) and put it into `Ostranauts/BepInEx/monomod`.
6. Put the mod into `Ostranauts\Ostranauts_Data\Mods`
7. Make sure that in `loading_order` put the mod at the bottom of the load order (below anything that changes the loot.json (which isnt compatible with FFU-BR)
8. Launch game, once in the main menu, exit (so FFR-BR can load in), relaunch

Unsure if you can bash the item.

**Have fun!**
