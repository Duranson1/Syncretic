# Syncretic
Beta, preserved just as it was intended, with modern fixes.

### Overview
Minecraft Beta Edition 1.7.3 - released in 2011, and the most popular version from Minecraft's "golden age." It perfectly encapsulates what the game is all about - pure creativity within an endless sandbox, yet many are deterred by its somewhat clunky playstyle. As with any beta release of a game, it is buggy and lacks many features that keep fans of modern Minecraft from giving it a real chance.

This modpack aims to change that. Running on a modified version of Fabric specifically for Beta 1.7.3, this modpack fixes many of those bugs while also backporting features loved by modern Minecrafters - all while maintaining vanilla parity.

### Features
- Increased render distance, while keeping the classic beta fog
- Brightness and FOV sliders added
- More debug info
- Rebindable debug keys
- Skin and authentication fixes
- Server list added
- Various performance enhancements
- Modern F5 mode
- Cloud height changed to 128 (height limit)
- Unsupported trapdoor placement
- Boat fixes
- Shears break dead bushes/tall grass
- Chests can open even with a block above them
- Fence shape and connection fixes
- Stairs craft 6
- Fixed slab placement
- Modern crafting recipes
- Trees drop apples
- Toggleable full recipe/item viewer
- Fixed inconsistent tool use on certain blocks
- Creative mode added
- Creative mode only music plays in survival
- Main menu panorama added
- Main menu theme added

### Important Notes
- Designed specifically for use with Prism Launcher v9.1+, and will not function correctly with other launchers
- Requires Java 17, and will not function with other Java versions
- Does not work out of the box - please thoroughly read installation instructions to insure proper installation
- If you find yourself dealing with any microstutters or lag, uncheck "Java arguments" in Syncretic's instance settings and paste the following into the Java arguments textbox:
```
-XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
```
- While this modpack is compatible with exisiting vanilla b1.7.3 worlds, practice regular backups as this still does remain a modified version of a very old game :)
- Multiplayer is largely untested and not guaranteed to work

### Installation Instructions
- Install Syncretic v2.0.5+ in Prism Launcher and ensure Java 17 is selected under Syncretic's instance settings
- Download Syncretic Babric Patches v1.0.0+ (found [here](https://github.com/Duranson1/syncretic-babric-patches/releases))
- Extract downloaded folder, inside are two items: a "patches" folder and a file named "mmc-pack.json"
- Drag both the "patches" folder and "mmc-pack.json" into Syncretic's instance folder, replacing the existing "mmc-pack.json" file
- Ensure the minimum and maximum memory allocation values in Syncretic's instance settings match
- Launch and enjoy :)

### Current WIP
- Translations
- Controller Support
- Fence Underside Texture Fix

_Syncretism is the practice of combining different beliefs and various schools of thought._
