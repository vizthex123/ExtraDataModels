This datapack adds more Data Models to [Hostile Neural Networks](https://www.curseforge.com/minecraft/mc-mods/hostile-neural-networks) and tweaks some of the existing ones.

Designed for my [Hi-Tech Revolution](https://curseforge.com/minecraft/modpacks/hi-tech-revolution) modpack.

_**Also includes trivia for all of them (the paragraph of text that appear in the Deep Learner) if you install the resource pack! Grab it alongside the [regular download](https://modrinth.com/datapack/extra-data-models/versions).**_

<br />

_**Suggest mods I should add support for on the [issue tracker](https://github.com/vizthex123/ExtraDataModels/issues), or on the [Discord](https://discord.com/invite/NtwzA6X)!**_

<br />

_Note: Since I made this for a 1.20 modpack, I'll start adding support starting on that version (but will still (back)port any changes I make - they just might take a bit longer to release)._

<br />

# Installation Instructions

1) After downloading the datapack, get [Open Loader](https://modrinth.com/mod/open-loader). *If you want the trivia entries, download the latest version of the [resource pack](https://modrinth.com/datapack/extra-data-models/versions) as well. It's attached to every datapack version, and works across all supported Minecraft versions.*

2) Place the datapack into `config/openloader/data`

3) **Optional:** Enable the trivia pack in the game's settings. _**If you downloaded it manually, you can place it into `config/openloader/resources` and it will auto-enable itself.**_

4) **Optional:** Load your world and check one of the models from the datapack to view its trivia entry. _**If the datapack isn't loaded, this resource pack won't do anything!**_

5) When updating the datapack, repeat step 2 - just override the .zip with the new one and it'll update everything. _**Same applies for manually updating the resource pack.**_

If you downloaded the trivia pack through a launcher, just enable it in-game (and make sure it's [enabled by default](https://modrinth.com/mod/default-options) if you plan to publish your modpack)

<br />

## 1.21

There are two ways to install this pack: Using [Open Loader](https://modrinth.com/mod/open-loader) and the CurseForge App (other launchers might work, but I don't use them so idk) or by using [Paxi](https://modrinth.com/mod/paxi).

*Paxi is the preferred method since it works like Open Loader did on 1.20 & earlier. Open Loader's devs changed the way packs are loaded and neglected to update either project page lol, but DeadPixels-512 figured out how it works so I've gone ahead and updated the instructions for it.*

<br />

### Paxi

1) Download [the mod](https://modrinth.com/mod/paxi) and [datapack](https://modrinth.com/datapack/extra-data-models/versions?g=1.21.1)

2) Place the datapack into `config\paxi\datapacks`

3) When updating the datapack, repeat step 2 - just override the .zip with the new one and it'll update everything. ***Same applies for manually updating the resource pack.***

4) **Optional:** Enable the trivia pack in the game's settings. ***If you downloaded it manually, you can place it into `config/paxi/resourcepacks` and it will auto-enable itself.***

5) **Optional:** Load your world and check one of the models from the datapack to view its trivia entry. ***If the datapack isn't loaded, this resource pack won't do anything!***

If you downloaded the trivia pack through a launcher, just enable it in-game (and make sure it's [enabled by default](https://modrinth.com/mod/default-options) if you plan to publish your modpack)

<br />

### Open Loader

1) Make sure the CurseForge App is installed. Other launchers should work if they have a section to download datapacks, though - that's the important part for this.

2) Download [the mod](https://modrinth.com/mod/open-loader), and in the instance for the modpack download the datapack (you can just search for `vizthex` to quickly find it, or copy & paste the project ID off of the CF page)

3) If you're using another launcher, make sure Open Loader's config file is set to load packs from wherever it's installed. It should just use vanilla's `datapacks` folder, which it covers by default - but if not, you'll have to add it yourself.

4) **Optional:** Enable the trivia pack in the game's settings. ***If you downloaded it manually, you can place it into wherever Open Loader stores stuff now (they forgot to update the CF page and tell us lol) and it should auto-enable itself.***

5) **Optional:** Load your world and check one of the models from the datapack to view its trivia entry. ***If the datapack isn't loaded, this resource pack won't do anything!***

If you downloaded the trivia pack through a launcher, just enable it in-game (and make sure it's [enabled by default](https://modrinth.com/mod/default-options) if you plan to publish your modpack)

<br />

# Mod Support
_Mod support only loads in if the mod(s) are also loaded into the game, so you don't need to install all of these mods._

### _For a full table of supported mods, [head here](https://github.com/vizthex123/ExtraDataModels/blob/main/CFAssets/support_table.md)._

*Note: Most Ad Astra mobs are variants due to the lack of drops. Martian Raptors only give items from [Thermal Expansion](https://modrinth.com/mod/thermal-expansion) and/or [Alex's Caves](https://modrinth.com/mod/alexs-caves) if either mod is installed.*

<br />

## Changes to Default Models

_Mod support will not load in unless the required mod is present, so you don't need to have everything installed_

- Several modded enemies are now variants for some default models (if the supported mod is loaded, of course)

- A few models now support some modded drops (such as the [Ender Dragon](https://github.com/vizthex123/ExtraDataModels/blob/main/data-pack/1.20/data/hostilenetworks/data_models/ender_dragon.json)). *For a full list, you can view the [source files](https://github.com/vizthex123/ExtraDataModels/tree/main/data-pack).*

- Adds a model for Salmon, Tropical Fish, Pufferfish, Skeleton Horses, Zombie Horses, and more!

- Adds Eggs to the Chicken's fabricator drops

- Adds [Glow Squid Tentacles](https://modrinth.com/mod/deeper_caves) to Glow Squids' fabricator drops

- Adds [Hoglin Meat & Hides](https://www.curseforge.com/minecraft/mc-mods/netherific) to Hoglin' fabricator drops (I recommend removing the default loot if you've got the mod installed).

- Adds [Alpha Roses](https://modrinth.com/mod/regions-unexplored) to Iron Golems' fabricator drops

- Removes Slime Blocks from the Slimes' fabricator drops