# Valheim-NeonPack Lite

The base mods required to join a world or server running [NeonPack 2.2.0][neonpack]

I've included a list of all the config changes I've made in the [github for the main modpack][github-extras]

I also use the following mods from NexusMods

_Required:_

- [Better Trader 1.0.6][better-trader]
- [Crush Antlers 0.1.0][crush-antlers]
- [Fitness Skill 1.0.3][fitness-skill]
- [Mod Config Enforcer 1.3.0][mod-config-enforcer]

I've included a template with an icon and an empty mod manifest.json in the [github for the main modpack][github-extras] to help add compatibility for NexusMods mods with r2modmanager

Simply add both files to the mod's .zip, then modify the manifest.json with the relevant mod's information

You can then do a simple drag'n'drop installation in r2modmanager with the .zip

## [Changelog][changelog]

Rather than continue to make this README even longer, I've seperated the changelog into its own page for ease of use

I will maintain a trimmed version of the full changelog within this README of only the most recent minor update and any subsequent patches

### Recent Updates

Version 2.2.0

```text
[Thunderstore]

  * Updated Epic Loot
    - 0.5.16 -> 0.6.3
  * Updated Valheim Armorstand
    - 0.0.1 -> 0.0.2
  * Updated Valheim Brawler
    - 0.0.4 -> 0.0.6

[NexusMods]

  - Removed Combat Evolved
    - 0.148.6 Valheim patch broke projectile interaction with the mod
    - Waiting on fix from mod dev
  - Removed Cooking Skill
    - 0.148.6 Valheim patch broke fermenter functionality
    - Waiting on fix from mod dev
  - Removed Fish Food
    - AssetBundle failing to load
    - Waiting on fix from mod dev
  - Removed Planting Plus
    - Issues regarding desync with certain interactables and combat
    - Waiting on fix from mod dev
  - Removed Sleep Without Spawn
    - Never really used the mod
    - Probable cause of world loading issue
```

[changelog]: https://github.com/NeonCarbide/Valheim-NeonPack-Lite/blob/master/CHANGELOG.md
[github-extras]: https://github.com/NeonCarbide/Valheim-NeonPack/tree/main/extras
[neonpack]: https://valheim.thunderstore.io/package/NeonCarbide/NeonPack/

<!-- Mod Links -->

[better-trader]: https://www.nexusmods.com/valheim/mods/433
[combat-evolved]: https://www.nexusmods.com/valheim/mods/301
[cooking-skill]: https://www.nexusmods.com/valheim/mods/483
[crush-antlers]: https://www.nexusmods.com/valheim/mods/590
[fish-food]: https://www.nexusmods.com/valheim/mods/531
[fitness-skill]: https://www.nexusmods.com/valheim/mods/388
[gathering-skill]: https://www.nexusmods.com/valheim/mods/342
[mod-config-enforcer]: https://www.nexusmods.com/valheim/mods/460
