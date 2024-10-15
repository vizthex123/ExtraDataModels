# Version Differences

Differences apply to all versions below the one it's listed in unless stated otherwise.

== 1.21 ==

- Name and display formatting was combined into a single object
- [1.21 Only] Loading condition is now `neoforge` and has slightly different syntax
- All the `item` fields are now `id`, with the exception of the input (apparently due to changes Mojang made to how the game handles items)


== 1.20 ==

- Default version for the pack (since I made it for [Hi-Tech Revolution](https://www.curseforge.com/minecraft/modpacks/hi-tech-revolution))


== 1.18 - 1.19 ==

- Entity field is called "type"
- Variants are called "subtypes"
- `empty_prediction` instead of `prediction_matrix`
- Both 1.18 and 1.19 use the same syntax
-- Exception: Name NBT (only used for the Sheep model)


== 1.17 ==

- No variants
- No optional output field
- Item amounts and RF costs are slightly different