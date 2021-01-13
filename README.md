# blockstates
List Minecraft (1.12.2) blockstates
(Blocks only, same trick goes with items)

minecraft/blockstates dir comes from:
%appdata%\.minecraft\versions\1.12.2\1.12.2\assets\minecraft\blockstates (1)

minecraft/block dir comes from:
%appdata%\.minecraft\versions\1.12.2\1.12.2\assets\minecraft\models\block (2)

minecraft/blocks dir comes from:
%appdata%\.minecraft\versions\1.12.2\1.12.2\assets\minecraft\textures\blocks (3)

From a names.txt list comes the following data: (example)

ID="1",DataValue="6",Item="smooth andesite",Description="Polished Andesite",IDName="(minecraft:stone)"

Some names are converted... (light grey <-> silver, polished <-> smooth) and (like oak wooden slab <-> oak slab)

The Item's spaces are converted to underscore, then the <Item>.json file is looked up in the blockstates dir. (1)

From the blockstates the block models are retrieved/collected.

These, with a (again) .json extension are looked up in the block dir. (2)

From this file the names of textures used are retrieved that are placed in the blocks (+'s'!)

Thank you pacman!

