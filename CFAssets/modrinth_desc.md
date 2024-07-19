This datapack adds more Data Models to [Hostile Neural Networks](https://www.curseforge.com/minecraft/mc-mods/hostile-neural-networks) and tweaks some of the existing ones.

Designed for my [High-Tech Revolution](https://curseforge.com/minecraft/modpacks/high-tech-revolution) modpack.



_**Also includes trivia for all of them (the paragraph of text that appear in the Deep Learner) if you install the resource pack! Grab it alongside the [regular download](https://modrinth.com/datapack/extra-data-models/versions).**_


_**Suggest mods I should add support for in the comments, on the [issue tracker](https://github.com/vizthex123/ExtraDataModels/issues), or on the [Discord](https://discord.com/invite/NtwzA6X)!**_


### Installation Instructions

1) After downloading the pack, get [Open Loader](https://modrinth.com/mod/open-loader).

1a) If you want the trivia entries, download the [resource pack](https://modrinth.com/datapack/extra-data-models/versions) as well.

2) Place the datapack into `config/openloader/data` and resource pack into `config/openloader/resources`

3) Load your world and the new models will be added to it. If a mod isn't loaded, the model/loot/changes won't load in.

4) When updating either one, repeat step 2 - just overrride the .zip with the new one and it'll update everything.

If you downloaded the trivia pack through a launcher, just enable it in-game (and make sure it's [enabled by default](https://modrinth.com/mod/default-options) if you plan to publish your modpack)

*For 1.16.5:*
Open Loader works differently on this version.

Packs are placed in the main install rather than the config folder (`openloader\data` instead of `config\openloader\data`). Same applies to resource packs going in the `resources` folder.


# Mod Support
_Mod support only loads in if the mod(s) are also loaded into the game, so you don't need to install everything._

|																																											|  1.17.1 | 1.18.X | 1.19.2 | 1.20.1 | Minimum Pack Version |
|----------------------------------------------------------------------------------------------------------------------------------------------|:-------:|:------:|:------:|:------:|:--------------------:|
| [Ad Astra](https://modrinth.com/mod/ad-astra)																						|         |    ✔   |    ✔   |    ✔   |                      |
| [Ad Astra: Proxima Plus](https://www.curseforge.com/minecraft/mc-mods/ad-astra-proxima-plus)	|         |        |        |    ✔   |                      |
| [Alex's Caves](https://modrinth.com/mod/alexs-caves)																			|         |        |        |    ✔   |                      |
| [Aquatic Frontiers](https://modrinth.com/mod/aquatic-frontiers)															|  nobody |    ✔   |    ✔   |    ✔   |                      |
| [Ecologics](https://modrinth.com/mod/ecologics)																					|   uses  |    ✔   |    ✔   |    ✔   |                      |
| [Ender Zoology](https://modrinth.com/mod/ender-zoology)																	|   this  |        |    ✔   |    ✔   |                      |
| [Galosphere](https://modrinth.com/mod/galosphere)																				| version |        |        |    ✔   |                      |
| [The Outer End](https://modrinth.com/mod/the-outer-end)																	|   lol   |        |        |    ✔   |                      |
| [Quark](https://modrinth.com/mod/quark)                   																			|         |    ✔   |    ✔   |    ✔   |                      |
| [Upgrade Aquatic](https://modrinth.com/mod/upgrade-aquatic)															|         |    ✔   |    ✔   |    ✔   |          1.1         |

<br/>
*Note: Most Ad Astra mobs are variants due to the lack of drops. Martian Raptors only give items from [Thermal Expansion](https://modrinth.com/mod/thermal-expansion) and/or [Alex's Caves](https://modrinth.com/mod/alexs-caves) if either mod is installed.*



Changes to Default Models
-------------------------

_Mod support changes will link to the mod's CurseForge page._
_Note: They will not load in unless the require mod is present, so you don't need to have everything installed_
 

- Several modded enemies are now variants for some default models (if the supported mod is loaded, of course)

- A few models now support some modded drops (such as the [Ender Dragon](https://github.com/vizthex123/ExtraDataModels/blob/main/data-pack/1.20/data/hostilenetworks/data_models/ender_dragon.json))

- Adds a model for Salmon, Tropical Fish, Pufferfish, Skeleton Horses, and Zombie Horses

- Llamas and Turtles were added in v1.4

- Adds Eggs to the Chicken's fabricator drops

- Adds [Dragon Scales](https://modrinth.com/mod/quark) to the Ender Dragon's fabricator drops

- Adds [Glow Squid Tentacles](https://modrinth.com/mod/deeper_caves) to Glow Squids' fabricator drops

- Adds [Hoglin Meat & Hides](https://www.curseforge.com/minecraft/mc-mods/netherific) to Hoglin' fabricator drops (I recommend removing the default loot if you've got the mod installed).

- Adds [Alpha Roses](https://modrinth.com/mod/regions-unexplored) to Iron Golems' fabricator drops

- Removes Slime Blocks from Slimes' fabricator drops