# Datapack Changelog

A full changelog for every version (and sub-version) of the [Data Pack](https://www.curseforge.com/minecraft/data-packs/extra-data-models).

This one will be updated more often than the CurseForge and Modrinth changelogs.

I increment the version by X.1 whenever I add more mod support (so long as the addition has 8+ models), and X.X.1 for minor fixes and/or additions I missed in the last patch. Version ports will be incremented by 1.X.

Lines appended with a version in brackets (e.g. [1.20] Text Here) denote changes that only apply to that version.

--------------------------------------------------

## 4.2.3

Added a model for the Sniffer<br />
Added a model for the Starfire Bird *[Eternal Starlight]*<br />
Fixed the Sheep model not giving Animal Fat if Hexerei is installed<br />
Equalised both Horse animal fat outputs to 24 (was 20 and 32)

Updated the Deepsilver drops for the Lunar Monstrosity and Lonestar Skeleton since the registry names were changed *[Eternal Starlight]*

Fixed a few missing egg drops:
- Crab *[Friends & Foes]*
- Spider *[Biomes o' Plenty]*
- Ice Spider *[Iron's Spells n' Spellbooks]*

Imported Autumnity support


<br /> <br />

--------------------------------------------------
## 4.2.2

Fixed a few models not loading properly (reported by warpalicious on the discord)<br />
Ported (the remaining) support for Mekanism Additions


<br /> <br />

--------------------------------------------------
## 4.2.1

Fixed [#7 (several models not loading in)](https://github.com/vizthex123/ExtraDataModels/issues/7)
- Also fixed several others that both people in that report missed

Disabled the model for the Tangled Hatred since the mod removed it *[Eternal Starlight]*
- If it gets re-added before I update the pack, you can change the `.txt` to `.json` to re-enable it


<br /> <br />

--------------------------------------------------
## 4.2

Added a model for the Ice Spider *[Iron's Spells n' Spellbooks]*<br />
The Wildfire now gives 1 Wildfire Crown Fragment *[Friends & Foes]*<br />
Renamed the Tower Squid model since the mod did the same *[Eternal Starlight]*

L_Ender's Catalysm changes:
- Reduced the amount of Crystallized Coral Fragments the Coral Golem gives
- Reduced the amount of Coral Chunks the Coralssus gives
- Doubled the Bone and Rotten Flesh output of Draugrs and Elite Draugrs
- Doubled the Ink Sac and Rotten Flesh output of Drowned Hosts
- Halved the drops for The Watcher
- Doubled the RF cost for The Prowler
- Fixed several models having incorrect RF amounts, predictions, or data requirements

Added support for the following:
- Aquatic Frontiers
- Atmospheric
- Buzzier Bees
- Draconic Evolution
- Ecologics
- L_Ender's Cataclysm
- More Useful Copper
- Oh The Biomes We've Gone
- Upgrade Aquatic
- YUNG's Cave Biomes


<br /> <br />

--------------------------------------------------

## 4.1

Fixed the Illusioner's name not being localized<br />
Reduced the amount of Netherite Scrap Ancient Knights give *[Iron's Spells n' Spellbooks]*

Imported the following changes from v3.5:

- Added a model for the Bee, Ravager, Pillager, and Vindicator
- The Bee model was suggested by Tyler489 on the Hostile Neural Networks discord server

Added support for Eternal Starlight (suggested by MrEizy on the Hostile Neural Networks discord server)


<br /> <br />

--------------------------------------------------
# Minecraft 1.21 - v4.0

## 4.0

Ported to 1.21.1

Most mod support has been removed for now, but I'll re-do it all as they do get ported (gonna be *so fun* to change the handful of lines that are different in all 300 files :D)

Added a model for the Breeze<br />
The Bogged is now a Skeleton variant


<br /> <br />

--------------------------------------------------
# Minecraft 1.20 - v3.0

## 3.10

Backported the Sniffer model I added in v4.2.3

Reduced the emerald gain from Pillagers to 4 (was 8)<br />
Reduced the Iron Golem's RF use to 512/t (was 1,024)<br />
Added Hexerei's Animal Fat to the Mooshroom model<br />
Increased the Skull and Rib Bone output for Skeleton Druids *[The Twilight Forest]*

Added support for Occultism and Cracker's Wither Storm (requested by [explodingtomatos544-code](https://github.com/vizthex123/ExtraDataModels/issues/8))


<br /> <br />

--------------------------------------------------

## 3.9.1

Adjusted the loot from a few of Aquatic Frontiers' mobs<br />
Added some missing mod compat drops to several models<br />
The Wildfire now gives 1 Wildfire Crown Fragment *[Friends & Foes]*<br />
Tweaked the data requirements for both mobs from YUNG's Cave Biomes<br />
Slightly increased the RF cost of both Squid Models so it matches modded Squids

L_Ender's Catalysm changes:
- Reduced the amount of Crystallized Coral Fragments the Coral Golem gives
- Reduced the amount of Coral Chunks the Coralssus gives
- Doubled the Bone and Rotten Flesh output of Draugrs and Elite Draugrs
- Doubled the Ink Sac and Rotten Flesh output of Drowned Hosts
- Halved the drops for The Watcher
- Doubled the RF cost for The Prowler
- Fixed several models having incorrect RF amounts, predictions, or data requirements

Added support for Oh The Biomes We've Gone


<br /> <br />

--------------------------------------------------

## 3.9

Reduced the RF cost of Cave Guardians *[Alex's Caves]*
- This refers to the boss of each cave (e.g. Hullbreaker and the Gum Worm)
- Increased the fabricator amounts for several of them

Reduced the output amounts of special items from Cave Guardians *[Alex's Caves]*
- This refers to the unique drops they have (such as the Sweet Tooth and Pure Darkness)

[Synclet](https://github.com/vizthex123/ExtraDataModels/issues/5) added support for the following:
- Ars Nouveau
- Bosses of Mass Destruction
- Mekanism Additions
- MythicBotany


<br /> <br />

--------------------------------------------------

## 3.8

Fixed the Iron Golem's scaling<br />
Increased the Skeleton Horses' Bone output<br />
Doubled the Iron output from Magnetrons *[Alex's Caves]*<br />
Added a few missing mod compat drops to the Ender Dragon

Added a Horse model for various modded horses (and vanilla ones, of course)<br />
Adjusted the fish outputs for Guardians and Elder Guardians<br />
Added some models that were missing from L_Ender's Cataclysm<br />
Increased the Purpur Golem RF cost to 512 (was 256) *[The Outer End]*

Added support for the following:
- Atmospheric
- Caverns & Chasms
- Cloud Storage
- Draconic Evolution (added by Synclet in [issue #4](https://github.com/vizthex123/ExtraDataModels/issues/4))
- The Endergetic Expansion (ported from 1.19)
- Environmental
- Mob Compack
- More Useful Copper
- Neapolitan (spider variant)
- Savage & Ravage
- Terramity


<br /> <br />

--------------------------------------------------

## 3.7.1

Fixed the Stable Ice Core's model not loading *[Twilight Forest]*
- Also reduced the amount of Thin Ice it gives (from 48 to 16)

Made a few mobs give their heads so things are consistent<br />
Martian Raptors now give 12 Sulfur Dust from Alex's Caves *[Ad Astra]*<br />
The Toretoise's yields for Lapis and Redstone is now 10 Lapis (was 8) *[Quark]*<br />
Added custom data requirements to Quark's Stoneling (since it's rare. Also increased its lapis output from 8 to 10)


<br /> <br />

--------------------------------------------------

## 3.7

Moved all of my custom models to their own namespace

Fixed Ice Cubes trying to give Ice from a mod that didn't exist. Also removed Ice Shards and Dragon Ice *[YUNG's Cave Biomes]*<br />
Fixed Sand Snappers trying to give Sand from a mod that didn't exist. Also buffed Ancient Sand output to 16 (was 8) *[YUNG's Cave Biomes]*

Buffed the amount of Ignitium Ingots given (from 6 to 8) *[L_Ender's Cataclysm]*<br />
Added Tinkers Construct support

Twilight Forest's Snow Queen model can now give modded Ice types<br />
Twilight Forest's Ice Elemental model can now give modded Ice types
- Also changed its name colour

Changed the colour of the Iceologer *[Friends & Foes]*<br />
Ender Dragon models now give 4 of each modded loot (was varying amounts)<br />
Reduced the Ravager's Hide output to 4 (was 8)

Added support for the following mods:
- The Conjurer
- Whisperwoods
- L_Ender's Cataclysm (suggested by yrarah in the CurseForge comments section)


<br /> <br />

--------------------------------------------------

## 3.6.1

Tweaked the RF usage of several models<br />
Slightly reduced the render scale of the Cow and Sheep<br />
Fixed the Elder Guardian's loot being in the wrong order<br />
Tweaked the order of the Fallen Knight's loot *[Ender Zoology]*


Martian Raptors now give 4 Slimeballs<br />
Pillagers now give 4 Crude Fragments *[Biome Makeover]* and 16 Silver Nuggets *[Galosphere]*<br />
Coral Golems now longer give the music disc *[Aquatic Frontiers]*<br />
Giant Squids now give 16 Cod (was 32) *[Aquatic Frontiers]*
- Reduced RF usage to 48/t (was 64)


<br /> <br />

--------------------------------------------------

## 3.6

Hoglins can now give Hogham *[Jaden's Nether Expansion]*<br />
Elder Guardians can now give Trident Shards from Additional Additions
- Reduced Trident Fragment count to 1 (was 2) *[Better Tridents]*

Added support for the following mods:
- Autumnity
- Buzzier Bees (as subtypes for the Cow and Alex's Mobs' Grizzly Bear)
- Jaden's Nether Expansion


<br /> <br />

--------------------------------------------------

## 3.5.1

Changed the colour of the Mimicube *[Alex's Mobs]*

Added models for the new mobs from Alex's Caves 2.0.0


<br /> <br />

--------------------------------------------------

## 3.5

*This is a massive update, and I'm hoping y'all enjoy it. I've gone back and checked on every model in the pack, so everything should be up-to-standard with all random issues/incorrectness fixed.*

Overhauled a lot of backend stuff
- Doesn't really affect players, but it does make development a bit easier

Rebalanced almost every Alex's Caves model based on my [new standards](https://github.com/vizthex123/ExtraDataModels/blob/main/standards.md#alexs-caves)
- The various references I sometimes make do override this standard though (which applies to every model)
- The old scaling for standard enemies was 4/8/16/24 kills to max a model
- The old scaling for bosses was 2/3/4/5 kills to max a model
- There's too many to list, but a few of the ones I changed before deciding to do an overhaul are listed below

<br />

Reduced the Mimicube's Ferrouslimeball output to 4 (was 8)<br />
Removed Feathers from the Subterranodon's drops<br />
Halved the Dinosaur Chop drops of all the Primordial Grotto mobs<br />
Added the Atlatitan's loot to the Luxtructosaurus
- It give a bit less while costing more RF (since it's a boss), but makes the model a tad more useful

Tweaked a few models from Alex's Caves:
- Brainiac now uses 256 RF/t (was 128)
- Teletor now uses 192 RF/t (was 128)
- Notor now uses 92 RF/t (was 64)

Adjusted the Hullbreaker's model
- Tweaked data rates
- Increased the Sea Glass Shard output to 32 (was 8)
- Moved the model preview upwards a bit so it's more centered

Tweaked the drops of the Deep One model
- Removed Gold Nuggets and increased Raw Gold to 3 (was 1)
- Tweaked the order so things are grouped together a bit better

<br />

Fixed several models giving the wrong generalized predictions<br />
All Ad Astra models now give End Predictions instead of Overworld<br />
Added models for the following mobs:
- Bee (suggested by Tyler489 on the Hostile Neural Networks discord server)
- Ravager
- Pillager
- Vindicator


Wraiths now give 4 of each Ectoplasm (from all the supported mods) *[Quark]*<br />
Marauder Pillagers (Cowboys) now have their own model *[Biome Makeover]*<br />
Increased the Slime Pearl output from Ferrouslimes *[Alex's Caves]* and Mimicubes *[Alex's Mobs]* to 4 (was 3)


Reduced the amount of Netherite Scrap Ancient Knights give *[Iron's Spells n' Spellbooks]*<br />
Halved the amount of Rotten Flesh (now 16) and Cheese (now 8) Star Crawlers give *[Ad Astra]*<br />
Changed the Wither to give Nether Predictions and require less data per tier<br />
The Goose is no longer a Chicken variant *[Upgrade Aquatic]*<br />
Removed End Crystals from Enderman models


Re-balanced the Stoneling's loot once again *[Quark]*<br />
Fixed Quark's Crab model using too much RF (was 128/t, now 48/t)<br />
Reduced the RF usage of Star Crawlers to 109/t (was 164/t) *[Ad Astra]*<br />
Reduced the RF usage of the Forgotten to 256/t (was 512) *[Quark]*<br />
Reduced the render size of the Annihilator so it fits better into the preview box *[Deep Dark: Regrowth]*<br />
Reduced the render size of the Bone Serpent, Bunfugus, and Guster *[Alex's Mobs]*


Added a separate model for the Wither Skeleton Knight and Wraither *[Bygone Nether]*
- Previously, they were Wither Skeleton subtypes

Added a separate model for the Fallen Knight *[Ender Zoology]*
- Previously, it was a Zombie and Skeleton variant


Added support for the following mods:
- Aquamirae
- Biome Makeover
- Bygone Nether
- Deep Dark: Regrowth


<br /> <br />

--------------------------------------------------

## 3.4

Alex's Mobs changes:
- Fixed the Void Worm's model trying to give an item that didn't exist<br />
- Fixed the scaling for the Laviathan, Moose, and Warped Mosco<br />
- Reduced the Rattlesnake's Rattle output to 8 (was 16)

Reverted the Phantom's text colour back to its default value (`#0AB405`)<br />
Ender Zoology models now give the correct predictions

Reduced the amount of Netherite Scrap Ancient Knights give *[Iron's Spells n' Spellbooks]*<br />
The Dead King's data model now requires far fewer kills to level up
- Also resized it so he fits into the preview window

Added support for the following mods:
- Ice & Fire (suggested by TravHan2009 in the comments section)
- YUNG's Cave Biomes


<br /> <br />

--------------------------------------------------

## 3.3

Fixed the pack format being wrong (I don't think it affects anything, but it bothers me if it's wrong)

Changed the colour for the Luxtructosaurus<br />
Increased the Scrap Metal (8 -> 16) and Copper Ingot (16 -> 64) outputs for the Hullbreaker
- Also changed the order so things are grouped together better
Removed extra matrix costs from all models

Added a data model for Llamas<br />
Added a data model for Turtles<br />
The Evoker model now gives 1 Totem of Undying (was 2)<br />
Reduced the amount of Ink Sacs given by Giant Squids *[Aquatic Frontiers]*

Added support for the following mods (suggested by AntiMidas in the comments section):

- Alex's Mobs<br />
- Friends & Foes *[1.18+] - Moobloom is a cow variant*<br />
- Iron's Spells 'n Spellbooks *[1.18+]*<br />
- Tetra *[1.18+ - drops only]* - Adds fabricator drops to the Ender Dragon


<br /> <br />

--------------------------------------------------

## 3.2.1

*This was the first version released on Modrinth.*

Fixed the Squirrel and Gloomoth models not loading


<br /> <br />

--------------------------------------------------

## 3.2

Fixed Ad Astra models trying to load in even if the mod isn't loaded

Changed the colour for Phantoms<br />
Reduced the amount of TE Sulfur Martian Raptors give<br />
Elder Guardians can now give Trident Fragments if Better Tridents is installed

Thrasher data models now give 8 teeth (was 12)<br />
Reduced the amount of Ender Fragments given by the Enderminy, Concussion Creeper, and Infested Zombie<br />

Frosted Skeletons can now give Ice Shards
- Reduced the amount of Ice Blocks given to 8

Nucleeper data models now require 512 RF/t (was 256)
- Now gives 2 Fissile Cores (was 4)
- Now gives 64 Gunpowder (was 48)

Added data models for the following mobs:
- Entombed *[The Outer End]*
- Spectrafly *[The Outer End]*
- Star Crawler *[Ad Astra]*


<br /> <br />

--------------------------------------------------

## 3.1

Added support for Upgrade Aquatic
- The Goose is a Chicken variant
- The Flare is a Phantom variant
- Guardian and Elder Guardian predictions can now be fabricated into fish from Upgrade Aquatic
- Other mobs have their own data models


<br /> <br />

--------------------------------------------------

## 3.0

_WARNING: This won't work unless all the mods are installed because I set it up wrong! Install a newer version instead!!_

Initial release.

Supports the following mods:

- Ad Astra
- Ad Astra: Proxima Plus
- Alex's Caves
- Aquatic Frontiers
- Ecologics
- Ender Zoology
- Galosphere
- The Outer End
- Quark


<br /> <br />

--------------------------------------------------
# Minecraft 1.19 - v2.0

## 2.2.1

Added animal fat drops to most modded mobs<br />
Re-added the Three Bolt Helmet to Captain Cornealia's fabricator drops *[Aquamirae]*


<br /> <br />

--------------------------------------------------

## 2.2

Backported most changes from v3.7 & onwards
- I'll only list the highlights here, but I did make sure to check all the supported mods on this version to try and find all the changes - but i'm sure i missed a few things since there's a lot of stuff to cover lol. As always, report bugs/feedback on the [issue tracker](https://github.com/vizthex123/ExtraDataModels/issues) or [discord server](https://discord.com/invite/NtwzA6X).
- Changes are obviously excluded if the mob(s) don't exist on this version

Added a model for the Glare *[Caverns & Chasms]*<br />
Fixed the Fallen Knight still counting as a Skeleton and Zombie variant<br />
Removed Ender Pearls from the Enderminy and reduced the Ender Fragment count to 20 (was 40)<br />
Removed my Wilden data models since Hostile Neural Networks already adds a model for them

Backported the models for the Horse, Mooshroom, Pig, Shulker, Spider, Warden, and Wither<br />
Changed the Crystalline Slime's Rose Quartz Cluster to a Shard *[Mob Compack]*<br />
Buffed the amount of Ignitium Ingots given (from 6 to 8) *[L_Ender's Cataclysm]*<br />
Changed the translation key for Upgrade Aquatic's Jellyfish
- This means you'll need v1.9.2 or newer of the Trivia Pack

Backported support for the following:
- Ars Nouveau
- Atmospheric
- Buzzier Bees
- Caverns & Chasms
- Cloud Storage
- Cracker's Wither Storm Mod
- Environmental
- Mekanism Additions
- Mob Compack
- MythicBotany
- Neapolitan
- Occultism
- Oh The Biomes You'll Go
- Savage & Ravage


<br /> <br />

--------------------------------------------------

## 2.1

Moved all of my custom models to their own namespace

Fixed Ice Cubes trying to give Ice from a mod that didn't exist. Also removed Ice Shards and Dragon Ice *[YUNG's Cave Biomes]*<br />
Fixed Sand Snappers trying to give Sand from a mod that didn't exist. Also buffed Ancient Sand output to 16 (was 8) *[YUNG's Cave Biomes]*

Twilight Forest's Snow Queen model can now give modded Ice types<br />
Twilight Forest's Ice Elemental model can now give modded Ice types
- Also changed its name colour

Changed the colour of the Iceologer *[Friends & Foes]*<br />
Ender Dragon models now give 4 of each modded loot (was varying amounts)<br />
Reduced the Ravager's Hide output to 4 (was 8)

Removed a model I didn't intend to include<br />
Iceologers can now give ice from Oh the Biomes We'll Go *[Friends & Foes]*<br />
Elder Guardians can now give Elder Guardian Spines *[Upgrade Aquatic]*

Reduced the RF cost of the Golden Moth to 24 (was 48) *[Aquamirae]*

Added support for the following mods:
- The Conjurer
- Enlightend
- Whisperwoods
- L_Ender's Cataclysm (suggested by yrarah in the CurseForge comments section)


<br /> <br />

--------------------------------------------------

## 2.0.2

Fixed the pack format being wrong<br />
Fixed the UI scaling for the Warped Mosco, Lavathian, and Moose


<br /> <br />

-----------------------------------------------------------------------------------

## 2.0.1

Fixed all my custom subtypes not loading<br />
Fixed the Phantom model not loading


<br /> <br />

--------------------------------------------------

## 2.0

Backported to 1.19.2

Removed Alex's Caves support since the mod isn't on this version<br />
Removed Galosphere support since the mobs aren't in this version

Added a data model for Star Crawlers since they've got drops in this version<br />
Added a data model for Camels *[Ecologics]*


<br /> <br />

--------------------------------------------------
# Minecraft 1.18 - v1.0

## 1.2

Moved all of my custom models to their own namespace<br />
The datapack no longer loads models if the mod they're for isn't installed.

Fixed Wraith models trying to output modded items even if the mod isn't loaded.<br />
Fixed Ice Cubes trying to give Ice from a mod that didn't exist. Also removed Ice Shards and Dragon Ice *[YUNG's Cave Biomes]*<br />
Fixed Sand Snappers trying to give Sand from a mod that didn't exist. Also buffed Ancient Sand output to 16 (was 8) *[YUNG's Cave Biomes]*

Twilight Forest's Snow Queen model can now give modded Ice types<br />
Twilight Forest's Ice Elemental model can now give modded Ice types
- Also changed its name colour

Changed the colour of the Iceologer *[Friends & Foes]*<br />
Ender Dragon models now give 4 of each modded loot (was varying amounts)<br />
Reduced the Ravager's Hide output to 4 (was 8)

Removed a model I didn't intend to include<br />
Added a model for the Ancient Paladin *[OB Core (Legacy)]*

Iceologers can now give ice from Oh the Biomes We'll Go *[Friends & Foes]*<br />
Elder Guardians can now give Elder Guardian Spines *[Upgrade Aquatic]*

Reduced the RF cost of the Golden Moth to 24 (was 48) *[Aquamirae]*

Added support for the following mods:
- The Conjurer
- Enlightend
- Whisperwoods
- L_Ender's Cataclysm (suggested by yrarah in the CurseForge comments section)


<br /> <br />

--------------------------------------------------

## 1.1

Backported to 1.18.X

Added a data model for Llamas<br />
Added a data model for Turtles<br />
The Evoker model now gives 1 Totem of Undying (was 2)<br />
Reduced the amount of Ink Sacs given by Giant Squids *[Aquatic Frontiers]*
Removed Totem loot from the Illusioner and Iceologer (since neither Totem is in this version)

Added support for the following mods (suggested by AntiMidas in the comments section):

- Alex's Mobs<br />
- Friends & Foes<br />
- Iron's Spells 'n Spellbooks<br />
- Tetra

<br />

Removed the following models (since the mobs aren't in this version):

*[Alex's Mobs]*

- Banana Slug<br />
- Blue Jay<br />
- Farseer<br />
- Mudskipper<br />
- Murmur<br />
- Potoo<br />
- Skreecher

<br />

*[Friends & Foes]*

- Tuff Golem<br />
- Wildfire

<br />

*[Iron's Spells n' Spellbooks]*

- Apothecarist<br />
- Priest


<br /> <br />

--------------------------------------------------

## 1.0

Backported to 1.18.X

Removed Aquatic Frontiers and Ender Zoology support<br />
Removed my Sheep changes since Ad Astra isn't on this version<br />
Fixed a few models not loading because I formatted things wrong<br />
Other changes from the 1.19 version


<br /> <br />

--------------------------------------------------

## 0.7

Dropped support for 1.17.1

_I hate having to drop support for a version people might play, but my test instance won't load and I can't fix it. In addition to this, all the mods I support either dropped support for or entirely skipped 1.17 since it's a half-baked version._

_I would suggest moving your modpack to 1.18.2 or later if you can do so, as this version was kind of forgotten since it's half-complete._


[All changes from v1.5](https://github.com/vizthex123/ExtraDataModels/blob/main/data-pack/changelog_data_old.md), 
excluding the following:
- Scaling fixes - Didn't affect 1.17
- Void worm fix - Was only on 1.20
- Random mod fixes - The mods aren't on this version
- Support for YUNG's Cave Biomes - Mod isn't on this version


Added models for the Sheep, Pig, Cow, Squid, and Glow Squid
- They're identical to the models on newer versions, but without the optional fabricator drops (since this version of the mod doesn't have it)
- The Sheep's has an off-white name label instead of the customized rainbow one


Standardized the file formatting
- Entirely a backend change, but it allows anyone modify things easier if they want to (and lets me make new models more efficiently)


<br /> <br />

--------------------------------------------------

## 0.6

Backported to 1.17.1

Removed all mod support drops since the method it uses doesn't exist in this version

Added support for Alex's Mobs<br />
Removed the following models (since the mobs aren't in this version):

- Bison<br />
- Catfish<br />
- Comb Jelly<br />
- Cosmic Cod<br />
- Endergrade - The mob exists, but I gave it drops from The Outer End, so it can't be used here<br />
- Flying Fish<br />
- Giant Squid<br />
- Rocky Roller<br />
- Skelewag


<br /> <br />

--------------------------------------------------

## 0.5

Backported to 1.17.1

Removed all mod support since nobody uses this version, so the supported mods aren't even here lol
- I figured I'd publish it anyway since it does tweak a couple of the default models, and maybe somebody's playing this half-finished MC version for god knows what reason and wants to use this datapack.

I don't know if this will even work (HNN wants Placebo v5.0.3, but it seems like that doesn't exist), so hopefully it's fine lol