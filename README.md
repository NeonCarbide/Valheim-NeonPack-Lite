# Valheim-NeonPack Lite

The base mods required to join a world or server running [NeonPack 2.10.0][neonpack]

I've included a list of all the config changes I've made in the [github for the main modpack][github-extras]

I also use the following mods from NexusMods

_Required:_

- [Combat Evolved 0.4.5][combat-evolved]
- [Cooking Skill 1.1.5][cooking-skill]
- [Crush Antlers 0.1.0][crush-antlers]
- [Fitness Skill 1.0.3][fitness-skill]
- [Mod Config Enforcer 1.4.1][mod-config-enforcer]

I've included a template with an icon and an empty mod manifest.json in the [github for the main modpack][github-extras] to help add compatibility for NexusMods mods with r2modmanager

Simply add both files to the mod's .zip, then modify the manifest.json with the relevant mod's information

You can then do a simple drag'n'drop installation in r2modmanager with the .zip

## [Changelog][changelog]

Rather than continue to make this README even longer, I've seperated the changelog into its own page for ease of use

I will maintain a trimmed version of the full changelog within this README of only the most recent minor update and any subsequent patches

### Recent Updates

Version 2.10.0

```text
[Thunderstore]

  + Added Better Continents 0.6.1
  + Added Item Drawers 0.4.0
  + Added Skyheim 1.0.4
  + Added Surtling Core Overclocking 1.0.1

  - Removed Comfort Calculation Tweaks
    - Was patched in one of the 0.148.x Valheim updates and forgot to remove
  - Removed Useful Trophies
    - Originally added due to lack of use for trophies other than decoration

  * Updated Creature Level and Loot Control
    - 3.5.0 -> 3.5.2
  * Updated Epic Loot
    - 0.7.2 -> 0.7.5
  * Updated Jotunn Lib
    - 0.1.4 -> 0.1.6

[NexusMods]

  * Updated Cooking Skill
    - 1.1.4 -> 1.1.5
```

[changelog]: https://github.com/NeonCarbide/Valheim-NeonPack-Lite/blob/master/CHANGELOG.md
[github-extras]: https://github.com/NeonCarbide/Valheim-NeonPack/tree/main/extras
[neonpack]: https://valheim.thunderstore.io/package/NeonCarbide/NeonPack/

<!-- Mod Links -->

[combat-evolved]: https://www.nexusmods.com/valheim/mods/301
[cooking-skill]: https://www.nexusmods.com/valheim/mods/483
[crush-antlers]: https://www.nexusmods.com/valheim/mods/590
[fitness-skill]: https://www.nexusmods.com/valheim/mods/388
[mod-config-enforcer]: https://www.nexusmods.com/valheim/mods/460
