Lines prefixed with a version in brackets (e.g. [1.20] Text Here) denote changes that only apply to that version.

[v1.5]
This is the first version with multi-version support for Minecraft!

As it says in the support tags, this version will work on MC 1.19.2 and 1.18.X. All future version for these two Minecraft version will follow suit.


Reduced the Rattlesnake's Rattle output to 8 (was 16)
Fixed the Void Worm's model trying to give an item that didn't exist [1.20]
Fixed the scaling for the Laviathan [1.20], Moose, and Warped Mosco [Alex's Mobs]
Reverted the Phantom's text colour back to the default (#0AB405)
Ender Zoology models now give the correct predictions

Reduced the amount of Netherite Scrap Ancient Knights give [Iron's Spells n' Spellbooks]
The Dead King's data model now requires far fewer kills to level up
- Also resized it so he fits into the preview window

Added support for the following mods:
- Ice & Fire (suggested by TravHan2009 in the comments section)
- YUNG's Cave Biomes [1.20 and 1.18 only]

	[1.21 Only]
	Ported to 1.21.1

	Most mod support has been removed for now, but I'll re-do it all as they do get ported (gonna be *so fun* to change the handful of lines that are different in all 300 files :D)

	Added a model for the Breeze
	The Bogged is now a Skeleton variant

--------------------
[v1.4]
[1.20] Fixed the pack format being wrong (don't think it affects anything, but it might prevent some random issues in the future)
Changed the colour for the Luxtructosaurus

Increased the Scrap Metal (8 -> 16) and Copper Ingot (16 -> 64) outputs for the Hullbreaker
- Also changed the order so things are grouped together better
Removed extra matrix costs from all models

Added a data model for Llamas
Added a data model for Turtles
The Evoker model now gives 1 Totem of Undying (was 2)
Reduced the amount of Ink Sacs given by Giant Squids [Aquatic Frontiers]

Added support for the following mods (suggested by AntiMidas in the comments section):

Alex's Mobs [All versions]
Friends & Foes [1.18+] - Moobloom is a cow variant
Iron's Spells 'n Spellbooks [1.18+]
Tetra [1.18+ - drops only] - Adds fabricator drops to the Ender Dragon

	[1.19 Only]
	Backported to 1.19.2

	Fixed the pack format being wrong

	Fixed the UI scaling for the Warped Mosco, Lavathian, and Moose

	[1.18 Only]
	Backported to 1.18.X

	Fixed the pack format being wrong
	
	Removed Totem loot from the Illusioner and Iceologer (neither Totem is in this version)

	Removed the following models (since the mobs aren't in this version):

	[Alex's Mobs]
	Banana Slug
	Blue Jay
	Farseer
	Mudskipper
	Murmur
	Potoo
	Skreecher

	[Friends & Foes]
	Tuff Golem
	Wildfire

	[Iron's Spells n' Spellbooks]
	Apothecarist
	Priest

	[1.17 Only]
	Backported to 1.17.1

	Removed all mod support drops since the method it uses doesn't exist in this version

	Added support for Alex's Mobs

	Removed the following models (since the mobs aren't in this version):

	[Alex's Mobs]
	Bison
	Catfish
	Comb Jelly
	Cosmic Cod
	Endergrade - The mob exists, but I gave it drops from The Outer End, so it can't be used here
	Flying Fish
	Giant Squid
	Rocky Roller
	Skelewag

--------------------
[v1.3.1]
Fixed the Squirrel and Gloomoth models not loading

	[1.19 Only]
	Fixed all my custom variants not loading
	Fixed the Phantom model not loading

	[1.18 Only]
	Backported to 1.18.X

	Removed Aquatic Frontiers and Ender Zoology support
	Removed my Sheep changes since Ad Astra isn't on this version
	Fixed a few models not loading because I formatted things wrong
	Other changes from the 1.19 version

	[1.17 Only]
	Backported to 1.17.1

	Removed all mod support since nobody uses this version
	- I figured I'd publish it anyway since it does tweak a couple of the default models, and maybe somebody's playing this half-finished MC version for god knows what reason and wants to use this datapack.

	I don't know if this will even work (HNN wants Placebo v5.0.3 but it seems like that doesn't exist), so hopefully it does lol

--------------------
[v1.3]
Fixed Ad Astra models trying to load in even if the mod isn't loaded

Changed the colour for Phantoms
Reduced the amount of TE Sulfur Martian Raptors give
Elder Guardians can now give Trident Fragments if Better Tridents is installed

Reduced the amount of Ender Fragments given by the Enderminy, Concussion Creeper, and Infested Zombie
Thrasher data models now give 8 teeth (was 12)
Frosted Skeletons can now give Ice Shards
- Reduced the amount of Ice Blocks given to 8
Nucleeper data models now require 512 RF/t (was 256)
- Now gives 2 Fissile Cores (was 4)
- Now gives 64 Gunpowder (was 48)

Added data models for the following mobs:
- Entombed [Outer End]
- Spectrafly [Outer End]
- [1.20 Only] Star Crawler [Ad Astra]


--------------------
[v1.2]
The datapack no longer loads models if the mod they're for isn't installed.
Fixed Wraith models trying to output modded items even if the mod isn't loaded.

	[1.19 Only]
	Backported to 1.19.2

	Removed Alex's Caves support since the mod isn't on this version
	Removed Galosphere support since the mobs aren't in this version

	Added a data model for Star Crawlers since they've got drops in this version
	Added a data model for Camels [Ecologics]


--------------------
[v1.1]
Added support for Upgrade Aquatic
- Guardian and Elder Guardian predictions can now be fabricated into fish from Upgrade Aquatic
- Flares are a Phantom variant
- Geese are a Chicken variant
- Other mobs have their own data models


--------------------
[v1.0] 
Initial release