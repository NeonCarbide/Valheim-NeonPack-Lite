# Valheim-NeonPack Lite

The base mods required to join a world or server running [NeonPack 2.6.0][neonpack]

I've included a list of all the config changes I've made in the [github for the main modpack][github-extras]

I also use the following mods from NexusMods

_Required:_

- [Combat Evolved 0.4.1][combat-evolved]
- [Cooking Skill 1.1.3][cooking-skill]
- [Crush Antlers 0.1.0][crush-antlers]
- [Fitness Skill 1.0.3][fitness-skill]
- [Mod Config Enforcer 1.4.1][mod-config-enforcer]
- [More Skills 0.1.54][more-skills]

I've included a template with an icon and an empty mod manifest.json in the [github for the main modpack][github-extras] to help add compatibility for NexusMods mods with r2modmanager

Simply add both files to the mod's .zip, then modify the manifest.json with the relevant mod's information

You can then do a simple drag'n'drop installation in r2modmanager with the .zip

## [Changelog][changelog]

Rather than continue to make this README even longer, I've seperated the changelog into its own page for ease of use

I will maintain a trimmed version of the full changelog within this README of only the most recent minor update and any subsequent patches

### Recent Updates

Version 2.6.0

```text
# 0.148.7 Valheim patch

[Thunderstore]

  + Added Name Tamed Animals 1.0.0

  * Updated Creature Level and Loot Control
    - 3.0.0 -> 3.2.0

[NexusMods]

  - Removed Better Trader
    - Causing long app start times due to loading 200+ trade options
    - Will try to find replacement

  * Updated More Skills
    0.1.5 -> 0.1.54
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
[more-skills]: https://www.nexusmods.com/valheim/mods/539
