# Mystical Extended Tier Bees

A small KubeJS datapack addon that adds **Productive Bees** resource bees for **Mystical Extended Tier**.

This pack adds four essence bees:

* Ornium Essence Bee
* Lightium Essence Bee
* Tornium Essence Bee
* Ouranium Essence Bee

It also includes English and Simplified Chinese language entries.

## Features

### New Bees

| Bee                  | Output           |
| -------------------- | ---------------- |
| Ornium Essence Bee   | Ornium Essence   |
| Lightium Essence Bee | Lightium Essence |
| Tornium Essence Bee  | Tornium Essence  |
| Ouranium Essence Bee | Ouranium Essence |

### Spawn Egg Crafting

The bee spawn eggs are crafted through an infusion altar-style recipe.

The center item is the previous tier bee spawn egg, and the pedestal items are:

* 4x essence of the same tier
* 4x essence blocks of the same tier

Progression:

```text
Insanium Bee Spawn Egg
→ Ornium Essence Bee Spawn Egg
→ Lightium Essence Bee Spawn Egg
→ Tornium Essence Bee Spawn Egg
→ Ouranium Essence Bee Spawn Egg
```

### Bee Behavior

* Bees cannot self-breed.
* Bees produce configurable honeycombs.
* Honeycombs can be processed in a centrifuge.
* Bee colors are based on their corresponding essence colors.

## Requirements

This addon requires:

* Minecraft 1.21.1
* NeoForge
* KubeJS
* Productive Bees
* Mystical Extended Tier
* Mystical Agriculture

## Installation

Copy the `kubejs` folder into your Minecraft instance or modpack root folder.

The final structure should look like this:

```text
.minecraft/
├─ kubejs/
│  ├─ assets/
│  ├─ client_scripts/
│  └─ data/
├─ mods/
├─ config/
└─ saves/
```

After installing, restart the game or server.

## Language Support

Included languages:

* English: `en_us`
* Simplified Chinese: `zh_cn`

Chinese names use the following translations:

| English  | Chinese |
| -------- | ------- |
| Ornium   | 奥尼姆     |
| Lightium | 光素      |
| Tornium  | 托尼姆     |
| Ouranium | 铀源      |

## Notes

This repository only contains KubeJS datapack and language files.

It does not include or redistribute any mod `.jar` files.

## Credits

This addon is designed for use with:

* Productive Bees
* Mystical Extended Tier
* Mystical Agriculture
* KubeJS
