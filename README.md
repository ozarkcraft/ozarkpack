[![Create Release](https://img.shields.io/github/workflow/status/ozarkcraft/ozarkpack/Create%20Release?style=for-the-badge)](https://github.com/ozarkcraft/ozarkpack/actions/workflows/main.yml)
[![Download Ozarkpack](https://img.shields.io/badge/download-ozarkpack.zip-blue?style=for-the-badge)](https://github.com/ozarkcraft/ozarkpack/releases/download/v0.1.1/ozarkpack-v0.1.1.zip)

# ozarkpack
OzarkCraft specific datapack

## Ozark Prize Loot Table
The Ozark Prize loot table has the following characteristics:
 * it rolls 2 - 10 times
 * it has 1 bonus role depending on luck
 * it will fill 10 slots with diamonds
   * each slot will contain between 1 and 10 diamonds with an 80% chance
 * it will fill 1 slot with 1 ancient debris with a 50% chance
 * Getting diamonds is 10 times more likely than ancient debris

Give yourself the loot with:
```
/loot give @a loot ozark:chests/ozark_prize
```
or create a chest with:
```
/give @p minecraft:chest{BlockEntityTag:{LootTable:"ozark:chests/ozark_prize"}} 1
```

## Functions
Make yourself super strong
```
/function ozark:strength
```

Setup a flatworld with day, clear weather, etc
```
/function ozark:start
```
