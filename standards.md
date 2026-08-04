# Standards

A list of standards I want to enforce when updating either pack.



# Both

Increment the version by X.1 whenever I add more mod support.
- X.X.1 for minor mod additions to the Trivia Pack



# Trivia

Add new trivia to the English translation (copied from Simplified English) and replace words with their proper spelling (e.g. "armour" instead of "armor")

Words to replace for proper english:

- Armor
- Color
- Gray
- Defense
- Favorite
- Crystallized
- Specialized
- Recognized
- Venomize


# Data

Standard indents I like
Removed `variants` if it's unused
Capitalized hex codes and make sure they start with #
Modloading condition on the top, with the mod ID below it
Folder names match the mod IDs formatting (shortened if needed)
Data amounts are multiples of base 2 (which is what computers use)



## Planned overhaul pack

Doesn't give equipment
- Exception: The Forgotten fom Quark, since that's the main point of it - plus, I like my trivia entry for it and having it only give boosted drops (or be a variant) feels a bit useless.

Doesn't give drops with special conditions (e.g. burn damage kill = cooked food)
- Exception: "Logical" drops (e.g. various foods Squirrels eat IRL from Ecologics' [Squirrel model](https://github.com/vizthex123/ExtraDataModels/blob/main/data-pack/1.20/data/hostilenetworks/data_models/ecologics/squirrel.json) - they might be carrying some around in-game and we just can't see it, ya know?)
Make sure the fabricator order is minecraft -> modded stuff (unless the primary drop is a mod item)
- Items first, then blocks

Drops tend to copy the mod's amounts, but I also made my own system based on the mob's base drops
- Range is based on the higher number of the drop (e.g 2 - 4 will give 8)
- Rare drops are usually excluded, but give 1 or 2 if I decide to include them
- Food drops give double (up to a maximum of 32)
-- 1 - 2 gives 4
-- 3 - 4 gives 8
-- 5 - 6 gives 12
-- 7 - 8 gives 16
-- 9 - 10 gives 32
-- 11+ gives 64



## RF drain rates
Boss: 2,560 RF/t (defined as "has a boss health bar and at least 200 health (100 hearts)")
- Exception: Eternal Starlight - bosses only drop Loot Bags, so they use 1,280 RF/t.

Miniboss: 1,024 RF/t (defined as "has at least 150 health (75 hearts) and no boss health bar")

Elites: 256 - 512 RF/t (depends on how good the drops are and their stats/how hard it is to fight)
- Mobs with 50 health (25 hearts) or rare, valuable loot are considered "elites"
Hostiles: 128 RF/t
Neutrals: 96 RF/t
Passives: 64 RF/t
- Non-fish water mobs use 48 (excludes hostiles)
- Fish use 32 (excludes hostile fish)
- Insects use 24



## Data & kill rates
Defaults:
- Data per tier: 6/54/354/1254
- Data per kill: 1/4/10/18
-- Kills per tier: 6/13.5/35.4/~69.6

*Data rate overrides are mostly unused for now (excluding Alex's Caves and a few mobs from various mods), but I might make a separate datapack or mod that uses them in the future.*

There's 4 levellable tiers in total (Faulty, Basic, Advanced, and Superior), with Self-Aware being the maximum tier
- Data rates follow factors of 8 or references to various things related to the enemy
-- Gained amount is `tier requirement/kills`. If it can't evenly divide, it gets rounded up to the nearest 1 (but for more common enemies, it can be rounded down)

--- Passives need 16/32/64/128 kills
--- Neutrals need 6/12/24/48 kills
--- Hostiles need 8/16/32/64 kills
---- Elites need 4/8/16/32 kills

--- Rare enemies need 2/4/6/12 kills

--- Minibosses need 1/2/3/6 kills
--- Bosses need 1/2/4/8 kills
--- Superbosses need 1/2/3/4 kills

<br />

passive data:
```
    "tier_data": [
		64,
        256,
        768,
        2048
    ],
    "data_per_kill": [
        4,
        8,
        12,
        16
    ]
}
```

1.21:
```
    "tier_data": {
        "faulty": 64,
        "basic": 256,
        "advanced": 768,
        "superior": 2048
    },
    "data_gained": {
        "faulty": 4,
        "basic": 8,
        "advanced": 12,
        "superior": 16
    }
}
```

<br />

neutral data:
```
    "tier_data": [
		48,
        192,
        768,
        2304
    ],
    "data_per_kill": [
        8,
        16,
        32,
        48
    ]
}
```

1.21:
```
    "tier_data": {
        "faulty": 48,
        "basic": 192,
        "advanced": 768,
        "superior": 2304
    },
    "data_gained": {
        "faulty": 8,
        "basic": 16,
        "advanced": 32,
        "superior": 48
    }
}
```

<br />

hostile data:
```
    "tier_data": [
		64,
        256,
        1024,
        4096
    ],
    "data_per_kill": [
        8,
        16,
        32,
        64
    ]
}
```

1.21:
```
    "tier_data": {
        "faulty": 64,
        "basic": 256,
        "advanced": 1024,
        "superior": 4096
    },
    "data_gained": {
        "faulty": 8,
        "basic": 16,
        "advanced": 32,
        "superior": 64
    }
}
```

<br />

elite data:
```
    "tier_data": [
		96,
        384,
        1536,
        6144
    ],
    "data_per_kill": [
        24,
        48,
        96,
        192
    ]
}
```

1.21:
```
    "tier_data": {
        "faulty": 96,
        "basic": 384,
        "advanced": 1536,
        "superior": 6144
    },
    "data_gained": {
        "faulty": 24,
        "basic": 48,
        "advanced": 96,
        "superior": 192
    }
}
```

<br />

rare data:
```
    "tier_data": [
		160,
        640,
        3840,
        15360
    ],
    "data_per_kill": [
        80,
        160,
        640,
        1280
    ]
}
```

1.21:
```
    "tier_data": {
        "faulty": 160,
        "basic": 640,
        "advanced": 3840,
        "superior": 15360
    },
    "data_gained": {
        "faulty": 80,
        "basic": 160,
        "advanced": 640,
        "superior": 1280
    }
}
```

<br />

miniboss data:
```
    "tier_data": [
		512,
        1920,
        3072,
        9216
    ],
    "data_per_kill": [
        512,
        960,
        1024,
        1536
    ]
}
```

1.21:
```
    "tier_data": {
        "faulty": 128,
        "basic": 1920,
        "advanced": 3072,
        "superior": 9216
    },
    "data_gained": {
        "faulty": 128,
        "basic": 960,
        "advanced": 1024,
        "superior": 1536
    }
}
```

<br />

boss data:
```
    "tier_data": [
		128,
        1024,
        4096,
        16384
    ],
    "data_per_kill": [
        128,
        512,
        1024,
        2048
    ]
}
```

1.21:
```
    "tier_data": {
        "faulty": 128,
        "basic": 1024,
        "advanced": 4096,
        "superior": 16384
    },
    "data_gained": {
        "faulty": 128,
        "basic": 512,
        "advanced": 1024,
        "superior": 2048
    }
}
```

<br />

superboss data:
```
	"tier_data": [
		128,
        1024,
        4096,
        16384
    ],
    "data_per_kill": [
        128,
        512,
        1366,
        16384
    ]
}
```

1.21:
```
    "tier_data": {
        "faulty": 128,
        "basic": 1024,
        "advanced": 4096,
        "superior": 16384
    },
    "data_gained": {
        "faulty": 128,
        "basic": 512,
        "advanced": 1366,
        "superior": 16384
    }
}
```

seems like 16384 is the limit for data values... kind of annoying, but whatever.



## Alex's Caves
Has different standards due to cave rarity & enemy sparsity

- Passives need 4/8/16/32
- Neutrals need 3/6/12/24
- Hostiles need 2/4/8/16
-- Elites need 3/6/9/12

- Cave Guardians (the bosses) need 1/2/3/4



### RF Rates
Cave guardian: 1,280 RF/t

Hostiles: 256 RF/t ("elite" enemies: 512 RF/t - defined as more the difficult mobs with unique drops)
Neutrals: 192 RF/t
Passives: 128 RF/t+ 
- Non-fish water mobs use 96
- Fish use 64
- Insects use 48



passive alex data:
```
    "tier_data": [
		64,
        256,
        1024,
        4096
    ],
    "data_per_kill": [
        16,
        32,
        64,
        128
    ]
}
```


neutral alex data:
```
    "tier_data": [
		96,
        384,
        1536,
        6144
    ],
    "data_per_kill": [
        32,
        64,
        128,
        256
    ]
}
```


hostile alex data:
```
    "tier_data": [
		128,
        512,
        2048,
        8192
    ],
    "data_per_kill": [
        64,
        128,
        256,
        512
    ]
}
```


elite alex data:
```
    "tier_data": [
		192,
        768,
        3072,
        12288
    ],
    "data_per_kill": [
        64,
        128,
        341,
        1024
    ]
}
```


cave guardian data:
```
    "tier_data": [
		256,
        1024,
        4096,
        16384
    ],
    "data_per_kill": [
        256,
        512,
        1365,
        4096
    ]
}
```