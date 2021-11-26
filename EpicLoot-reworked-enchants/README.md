# Epic Loot reworked enchants

This mod contains config files for Epic Loot that 
* change the basic list of available enchants (removed some, reworked some to only apply meaningfully, like
  you would only want to have "Recall" ability on spears that are throwable and removes throwable for other
  weapon types).
* adds some new recipes how to combine and up-craft enchanting materials.
* adds some other handy recipes like being able to craft chain item from iron bars.

## Other recommended mods

Here is a list of other mods / mod packs I created and like to use myself for single player (but those could also be
used on servers, if the server admins install them):
* [Single Player Essentials](https://valheim.thunderstore.io/package/FixItFelix/SinglePlayer_Essentials/)
  -> another mod pack with some features I personally like
* [Single Player Base](https://valheim.thunderstore.io/package/FixItFelix/SinglePlayer_Base/)
  -> another mod pack with some features I personally like
* [Regenerative Nature](https://valheim.thunderstore.io/package/FixItFelix/RegenerativeNature/)
  -> using [SpawnThat](https://valheim.thunderstore.io/package/ASharpPen/Spawn_That/) to respawn natural resources
  like tin and some trees and rare seeds
* [No Skill Drain](https://valheim.thunderstore.io/package/FixItFelix/NoSkillDrain/) -> on death your gained
  skills aren't lowered
* [Item Configs for CLLC](https://valheim.thunderstore.io/package/FixItFelix/CreatureLeveLAndLootControl_itemconfig/)
  -> this mod added ItemConfig*.yml files for
  [CLLC](https://valheim.thunderstore.io/package/Smoothbrain/CreatureLevelAndLootControl/) mod
* [Reworked enchants for EpicLoot](https://valheim.thunderstore.io/package/FixItFelix/EpicLoot_reworked_enchants/)
  -> adds enchanting recipes and available enchants for
  [EpicLoot](https://valheim.thunderstore.io/package/RandyKnapp/EpicLoot/) mod since the author created a lot enchants
  that don't make too much sense for me and I added some more handy recipes.

## Installation

### Epic Loot manual steps

To actually make this modpack work properly, you will need to do some manual steps, since Randy still didn't choose to make his loot mod to 
also support custom configs by reading file from config folder. You will need to go to the modpack folder (where TMM did install it into 
the profile) and copy around the custom configs to make them work. Starting the game without this step will load the default configs for 
EpicLoot, which screws up the game a lot, since the loot is way to powerful and the game gets boring by this - imho.

Steps:
1. go to TMM client
2. click "settings" button on the left
3. click "locations" tab on the top of the right selection menu
4. click "browse profile folder" -> a windows explorer should be opened
5. switch to the window of the windows explorer
6. navigate into folders "BepInEx\config\EpicLoot"
7. copy all files inside that folder
8. navigate into folder (again starting from profile folder) "BepInEx\plugins\RandyKnapp-EpicLoot"
9. paste all the files there and accept to overwrite any existing files

(if you wanna help to making this easier, I guess Randy will be happy to get that feedback on discord, maybe he changes his mind some time)

## Changelog

1.0.0 -> first version

## Contact

* https://github.com/FelixReuthlinger/epic-loot-configs
* Discord: Flux#0062 (you can find me around some of the Valheim modding discords, too)
