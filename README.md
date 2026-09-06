# Craftable Ancient Civilization Parts

Adds a recipe for **one Ancient Civilization Part**:

| Material | Amount |
| --- | ---: |
| Paldium Fragment | 20 |
| Refined Ingot | 2 |

The recipe has a workload of **1,000** and unlocks at level 19 for one
Technology Point.

The mod explicitly classifies Ancient Civilization Parts as a Rank 4 processing
material, which is the crafting-station ceiling used by Palworld's advanced
workstations. This makes the recipe eligible for Assembly Lines and Workshops
without changing the buildings or unrelated recipes.

## Requirements

- UE4SS
- PalSchema 0.6.4 or later

## Installation

Extract the `CraftableAncientParts` folder into:

`<Palworld>/Pal/Binaries/Win64/ue4ss/Mods/PalSchema/mods/`

Install it on the server and every connecting client, then restart the game or
server to load it. The server was not restarted while creating this package.

## Compatibility

Patches the `PalCrystal_Ex` recipe/category data and adds the
`CraftableAncientParts` technology row. It will conflict with a mod that
changes the Ancient Civilization Parts recipe or item category.
