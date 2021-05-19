# Vextrove's Terrain Datapack
This datapack improves upon the default terrain by adding more variety to the types of stone you will find underground.
The world is 384 blocks tall, ranging from y: -64 to y: 320.
It also adds several world types, in the form of new dimensions.
Additionally, it adds some minor gameplay modifications, such as:
 - You can use [most stone types](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/Vextrove's%20Terrain%20Datapack/data/minecraft/tags/items/stone_crafting_materials.json) as a substitute for cobblestone when crafting
 - You can climb [more blocks](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/Vextrove's%20Terrain%20Datapack/data/minecraft/tags/blocks/climbable.json), such as fences and chains. You will be able to climb the fence, but you still won't be able to jump over!
 - Endermen can pick up [a wide variety of blocks](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/Vextrove's%20Terrain%20Datapack/data/minecraft/tags/blocks/enderman_holdable.json)
 - [Deepslate blocks burn soulfire.](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/deepslate_soul_fire.png) Why? It looks cool.
 - You need Iron tools or better to mine Deepslate blocks
 - Some blocks require different tools than normal to be mined: [Pickaxe]() [Axe]() [Shovel]() [Hoe]() [Sword]()

**[LEAVE SUGGESTIONS HERE](https://github.com/Vextrove/vextrove_terrain_datapack/discussions/new)**

## Terrain generation changes
### Overworld
![A portal room made of Deepslate Bricks](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/deepslate_stronghold.png "A portal room made of Deepslate Bricks")
![A Stronghold fountain made of Deepslate Bricks](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/deepslate_fountain.png "A Stronghold fountain made of Deepslate Bricks")
![A Stronghold corridor made of Deepslate Bricks](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/deepslate_corridor.png "A Stronghold corridor made of Deepslate Bricks")
![A monster dungeon made of Cobbled Deepslate](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/deepslate_dungeon.png "A monster dungeon made of Cobbled Deepslate")
 - Deepslate strongholds below y: 0
 - Terrain is slightly smoother
 - Deeper ravines and crevices
##### Stone types
![A generic cave](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/cave.png "A generic cave")
![Various igneous rock types in a cave](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/cave_wall.png "Various igneous rock types in a cave")
 - Andesite (above y: 0)
 - Granite (above y: 0)
 - Diorite (above y: 0)
 - Dirt (from y: 56 to y: 80)
 - Gravel (from y: 8 to y: 56)
 - Tuff (from y: 4 to y: 56)
 - Deepslate (from y: 0 to y: 16)
 - Smooth Basalt (from 8 above bottom to 56 above bottom)
 - Blackstone (up to 24 blocks above bottom)
 - Magma (just under lava level)
#### Jungle biomes
![A more tropical Jungle](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/jungle_foliage.png "A more tropical Jungle")
![The underground Jungle](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/jungle_cavern.png "The underground Jungle")
 - A more tropical color
 - Underground grass
#### Swamps
![Clay, Dripleaves and huge mushrooms in a Swamp](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/swamp.png "Clay, Dripleaves and huge mushrooms in a Swamp")
![A dank Swamp cave tunnel](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/swamp_cave.png "A dank Swamp cave tunnel")
 - Huge mushrooms
 - Clay
 - Dripleaves
#### Mushroom islands
![A variety of huge mushrooms](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/huge_mushrooms.png "A variety of huge mushrooms")
![The underground of a Mushroom Island](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/mushroom_cavern.png "The underground of a Mushroom Island")
 - Huge mushrooms underground
 - More variety in huge mushrooms
#### Lush caves
![Foliage in a Lush Cave](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/lush_foliage.png)
 - Foliage (grass and leaves) color matches that of moss and dripleaves
 - Tropical water
#### Dripstone caves
![Murky water](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/murky_water.png "Murky water")
![A dungeon that has been covered by dripstone](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/dripstone_dungeon.png "A dungeon that has been covered by dripstone")
 - Murky water
#### Cold biomes
![A cave that has been frozen](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/frost_cavern.png "A cave that has been frozen")
![A frozen dungeon](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/frost_dungeon.png "A dungeon that has been frozen")
![A bridge over lava](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/unfortunate_bridge.png)
 - Ice caverns
 - Blue ice patches
 - Frozen water underground, making for an interesting underground ice swimming experience!
#### Desert biomes
![A desert cavern](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/desert_cave.png "A desert cavern")
 - Smooth Sandstone caverns
 - No Andesite or Diorite
 - Sand generates instead of Gravel
#### Mesa biomes
![A badlands cavern](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/mesa_cave.png "A badlands cavern")
 - Smooth Red Sandstone caverns
 - Red Sand generates instead of Gravel
 - Terracotta instead of Stone
#### Ocean biomes
![A Prismarine ocean cavern](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/prismarine_cavern.png "A Prismarine ocean cavern")
 - Ocean water has transformed the stone into Prismarine
#### Beach biomes
![Dripstone in a beach cave](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/beach_cavern.png "Dripstone in a beach cave")
 - Dripstone (due to water from the oceans making the caves humid)
#### Mountain biomes
 - Marble caves (Smooth Quartz)
#### Hill biomes
![A calcite cliffside](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/calcite.png "A calcite cliffside")
 - Calcite (around surface height)
#### Podzol biomes
 - Coarse dirt
### The Nether
![Magma at the bottom of the world](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/magmafication.png "Magma at the bottom of the world")
![Blood](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/blood.png "Blood")
![Foliage in a Warped Forest](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/warped_foliage.png)
![Foliage in a Crimson Forest](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/crimson_foliage.png)
![Foliage in a Basalt Delta](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/basalt_foliage.png)
![Foliage in a Soul Sand Valley](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/soul_foliage.png)
![Foliage in the Nether Wastes](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/nether_foliage.png)
![Huge mushrooms in the Nether Wastes](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/nether_mushrooms.png "Huge mushrooms in the Nether Wastes")
![A deteriorating Nether Fortress](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/deteriorating_fortress.png "A deteriorating Nether Fortress")
![A Nether Fortress with cracked bricks](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/cracked_fortress.png "A Nether Fortress with cracked bricks")
 - Charred Netherrack (Blackstone) at the bottom of the world
 - Nether biomes have a matching foliage color
 - Blocks turn into magma above the lava ocean
 - Water turns into blood
 - Nether bricks glow (Red Nether Bricks) in the hottest part of the Nether
 - The Nether has a day/night cycle, meaning that brightness increases and decreases slightly over time
### The End
![Purple water in the End](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/end_water.png "Purple water in the End")
![Foliage in the End](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/end_foliage.png)
 - Water is purple in the End
 - The outer islands have a custom foliage color

## Added dimensions
Use /execute in vextrove:<dimension name> run tp ~ 96 ~ to access these.
### 1024
![A colossal mountain](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/1024_mountain.png "A colossal mountain")
![A colossal hill](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/1024_hill.png "A colossal hill")
![A snowy mountain](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/snowy_mountain.png "A snowy mountain")
A world 1024 blocks in height. Ranges from -256 to 768
### Max (laggy)
A world 4064 blocks in height, the highest amount possible. Ranges from -2032 to 2032. I dare you to spelunk all the way to the bottom. Reaching -2000 counts as a win. Bonus points if you can do it without mining any deepslate! Either way, it will probably take you over an hour. How fast can it be done? 
### Beta (doesn't work yet)
A recreation of Minecraft 1.7.3 terrain. Will likely range from -64 to 128
### The Aether
![Forgotten Highlands](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/aether.png)
![An Irradiated Forest](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/irradiated_forest.png)
A basic imitation of the classic Aether mod. Ranges from 0 to 128
### The Skylands
![The bottom of the Skylands](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/skylands_deep.png "The bottom of the Skylands")
![A Birch Forest](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/skylands_birch.png)
![Overlooking a hole in a skyland](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/skylands_view.png)
![A Spruce Forest](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/skylands_spruce.png)
A 1024 block tall floating islands world. Ranges from -256 to 768
### Caverns
A 512 block tall cave world. Ranges from -128 to 384
### Dripstone Caverns
![A colossal dripstone](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/giant_dripstone.png "A colossal dripstone")
![A stalagmite that has fallen over](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/fallen_stalagmite.png "A stalagmite that has fallen over")
![A dripstone cavern](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/dripstone_cavern.png "A dripstone cavern")
A 256 block tall dripstone cave world. Ranges from -192 to 64
### Lush Caverns
![A lush cavern](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/lush_cavern.png "A lush cavern")
A 256 block tall lush cave world. Ranges from -192 to 64

## To-do List
 - Optimize stone types
 - Get Soulsand Valley to generate Skeleton skulls on the floor again
 - Get Chorus Trees to generate underneath overhangs again
 - Modify giant speleothem parameters from scratch
 - Investigate Coral
 - Figure out why Swamps are generating so damn many small Brown Mushrooms
 - Generate Shroomlight on the underground Mushroom Island ceiling
 - Underground Lilypads in Swamp
 - Look into increasing variation in tree height
 - Look into generating different biomes at different vertical levels in the Nether
 - Get Beta terrain working as intended
 - Learn more about structures/custom structures so I can use them to do cool things
 - Look into generating a giant tree (Yggdrasil)
### Website
 - Customize discussions page
 - Add videos
 - Create Github page
#### Add images
 - Cavern world
 - Mountain quartz
 - Better badlands cave picture
 - Elder Prismarine + Elder Prismarine Bricks
 - Dark Prismarine Wall
 - Sakura planks
 - Sakura leaves
 - Sakura logs
 - Purpur Chorus log
 - Teal Chorus log
 - Purpur Chorus planks
 - Teal Chorus planks
### On hold until new customization options become available
 - Get [Brown Mooshrooms](https://static.wikia.nocookie.net/minecraft_gamepedia/images/4/4e/Brown_Mooshroom_JE2.png) to spawn naturally on Mushroom Islands - Can't configure mob spawns with specific data values (last checked 21w19a)
 - Raise cloud height in the 1024 and 4064 block tall world types - Cloud height is hard-coded (last checked 21w19a)
 - Underground trees - The game won't generate trees where there is no sunlight (last checked 21w19a)
 - Make better use of 4064 block tall world (I have to put my ideal vision on hold due to a minor limitation I'll elaborate on later)
 - Get structures to generate above y: 128 (particularly in the Nether) - Structures are hard-coded to generate at specific ranges of y levels (last checked 21w19a) 
 - Generate large quartz crystals (reskinned large dripstones) in the highest part of the Nether Wastes - Large dripstones are hard-coded to only generate below y: 0 (last checked 21w19a)
 - Get [Chicken Jockey Towers](https://static.wikia.nocookie.net/minecraft_gamepedia/images/5/51/Chicken_Jockey_Tower.png) to spawn - Can't configure mobs to spawn riding other mobs (last checked 21w19a)
Please let me know if any of this has changed!

## Videos
 - 
 - 
 - 

## Resource pack/Datapack recommendations
 - [Lime's Advancements datapack](https://github.com/slicedlime/LimesAdvancements)
 - [myuusubi's FabulousHDR resource pack](https://www.curseforge.com/minecraft/texture-packs/fabulous-hdr)

## Minecraft ideas
This is my personal list of ideas of things to add to Minecraft. Most of these are my own, however a couple of them came from other people.
Roughly ordered from best to worst, based on how good the concept is and how much I like it, divided by how difficult I think it would be to implement. That being said, I am not a programmer...
Some of the worse ideas are higher up in the list than they should be, due to being grouped together with other ideas
These ideas are here so they may inspire me when adding features to this datapack.

### ★★★★★ Directional damage (Fix MC-26678)
### ★★★★★ [Chainstone - Suggested by gnembon/SciCraft](https://youtu.be/8UB0w8pbJ1Q)
 - Great steampunk vibes!
### ★★★★★ Ignore tall grass when attacking entities
### ★★★★☆ Ghast charging fireball animation (Fix MC-165038)
### ★★★★☆ Water on top of lava forms tuff rather than Cobblestone
### ★★★★☆ Dynamic cloud patterns (A moving random noise map, multiplied by a heightmap of the terrain)
 - This will make it so that clouds will not go through solid terrain
### ★★★★☆ Stacked Dispenser crafting recipe (Bow recipe with a Dropper in the middle) - Suggested by [ilmango](https://www.youtube.com/c/ilmango)/SciCraft

### Inventory:
#### ★★★★☆ Increase amount of inventory slots
 - One or two additional rows would be great
#### ★★★☆☆ Inventory sort button
### ★★★☆☆ Enable datapacks to add custom blocks
### ★★☆☆☆ Lava "melts" blocks it comes in contact with (like concrete powder)
 - Cobblestone -> Stone
 - Sand -> Sandstone
 - Red Sand -> Red Sandstone

### Tools:
#### Tool animations:
##### ★★★★★ Different animations for different tools
 - Shovel: Digging motion
 - Pickaxe: Swinging motion
 - Axe: Sideways chopping motion
 - Hoe: Tilling motion
 - Sword: Slashing motion
###### Attacks require different animations (their current one would suffice but isn't ideal)
#### ★★★☆☆ Different mining cracking patterns depending on what block is being broken and/or what tool is being used
 - Logs + Axe: cutting pattern
 - It does not make sense for some blocks to appear to break like they currently do

#### Hoes:
##### ★★★★☆ Hoes take time to till soil
 - Higher tiers are faster, but tilling shouldn't take too long
 - Different blocks take different times to till
##### ★★☆☆☆ Hoes break crops/tall grass/flowers in a 3x3 area
 - Range might be increased with enchantments
##### ★★☆☆☆ Hoes only destroy fully grown crops
 - Like how wielding a sword in creative mode prevents you from breaking anything
 
#### ★★★★☆ Random block picker
 - Some builds use a palette of multiple blocks to create a textured surface - an example of this are the Nylium/Netherwart surfaces in Netherwart forests. This item would greatly help create such patterns.
#### ★★★☆☆ Boomerang
 - Makes a circular motion
 - With enchantments, it can hit more than one target without falling
 - Fits with Minecraft's "medieval" aesthetic
#### ★☆☆☆☆ Infinity on water/lava buckets - Suggested by unknown
 - Great for building :)
 - Great for grieving >:)
 - Creative mode already has it - in survival mode, you just have to tediously replenish from your 2x2 infinite water source
 - Renewable Lava

### Decorative blocks:
#### ★★★★★ Frosted glass
 - The opposite of tinted glass; an opaque block that lets through light.
 - Crafted by resmelting glass blocks
 - Comes in "all 16 colors"
#### ★★★★★ Elder Prismarine
 - Prismarine with the Elder Guardian color palette
 - Can be crafted into Elder Prismarine Bricks
#### ★★★★★ Dark Prismarine Wall
#### ★★★★☆ Soul Sandstone?
 - Various Soul Sandstone Brick blocks
#### ★★★☆☆ Red Nether Bricks:
##### Red Nether Brick Fence
##### Cracked Red Nether Bricks
##### Chiseled Red Nether Bricks
#### ★★★☆☆ [Cherry blossoms](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Kenrokuen-kumagai1.jpg/1024px-Kenrokuen-kumagai1.jpg)
 - Pink planks
 - Pink leaves
 - Dark grayish brown logs
### ★★☆☆☆ Fence Post
 - A fence type that doesn't connect to surrounding blocks
### ★☆☆☆☆ Wall Post
 - A wall type that doesn't connect to surrounding blocks
### ★☆☆☆☆ Dual-type slabs??

### Minecarts:
#### ★★★★☆ Rails don't need a supporting block
 - We would need to be able to stand on rails as well for this to be any good
#### ★★★☆☆ Vertical rails
#### ★★★☆☆ Vertical rails
 - A Minecart would require Powered Rails to go up
#### ★★★☆☆ Increase Furnace Minecart tensile strength
 - Currently Minecarts split up when making a turn

### Biomes:
#### ★★★☆☆ Altitude-dependent biome generation
 - Different biomes generate at different heights
 - It appears this will be implemented in 1.18 with the new mountains, and hopefully the upcoming cave biomes as well
 
#### Caves:
##### ★★★★★ Local stone types
 - ★★★★☆ [Frozen caves](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/frost_cavern.png)
 - ★★★★☆ [Sandstone caves](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/desert_cave.png)
 - ★★★★☆ [Terracotta caves](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/terracotta_cave.png)
 - ★★☆☆☆ Marble caves
 
##### Slimes:
 - ★★★★★ Slimes should occasionally spawn underground, especially in Lush Caves (not just in Slime chunks)
 - ★★★★★ Slime size should either scale linearly or exponentially, not logarithmically like they currently do
 - ★★★★☆ Slimes should have an RGB data value either scale linearly or exponentially, not logarithmically like they currently do
 - ★★★☆☆ Slimes should rarely spawn at bigger sizes
###### Overhaul Slime chunks
 - Needs a visual cue, perhaps remove Slime chunks and replace them with a slimy cave biome

#### ★★★☆☆ Dynamic biomes
 - e.g. plant a lot of Jungle trees to create artificial Jungle biome, snow to create a cold biome, etc.
 - Special variations depending on the dimension the biome is in, e.g Hot Jungle Biome (Red foliage? Special mobs?)

### Functional blocks:
#### ★★☆☆☆ Moving platform block
 - Moves horizontally or vertically
 - Entities can stand on them without falling off
#### ★★☆☆☆ Eye block
 - Activates by entities looking at it
 - Looking at the center causes a stronger Redstone signal output (like the Target block)
#### ★☆☆☆☆ Teleporters
 - Have to be synced up with each other
#### ★☆☆☆☆ Speaker block
 - Plays sounds

### Sound:
#### ★★★★☆ Make block sounds .json dependent
 - Could possibly run on a seperate thread? Supposedly Minecraft only employs one CPU core while most devices have at least two
#### ★★★★☆ Sound filtering
 - Underwater - and even more so "underlava" - higher frequencies are filtered out, muffling the sound
#### ★★★☆☆ Echo sound filter
 - Either do a rudimentary calculation of cave size, or enable when skylight level is zero and current altitude is below y: 24
 
#### Block sounds:
 - Give all brick blocks Netherbrick sounds rather than the generic Stone block sound
 - Unique sound for Cobblestone and Raw Metal blocks
 - Enchanting Table (magical sound)
 - Unique sound for Clay
#### ★☆☆☆☆ Biome and altitude dependent ambient noises
 - Birds in forests and especially jungles
 - Wind high up in the mountains and perhaps in deserts
 - Shore wave sounds coming from the direction of ocean biomes in beach biomes
 
### The End:
#### ★★☆☆☆ Chorus moss block
 - ★★★★☆ Like Grass blocks, but the moss grows on the bottom face of Endstone instead of on the top
 - ★★★☆☆ Let's call it Chorus/Ender/Purpur Moss, just to differentiate it from grass
#### "Wood" types
 - ★★☆☆☆ Purpur "wood" type [(Purple)](https://static.wikia.nocookie.net/minecraft_gamepedia/images/1/1f/Nether_Portal_%28EW%29_BE.gif)
 - ★★☆☆☆ Ender "wood" type [(Teal)](https://static.wikia.nocookie.net/minecraft_gamepedia/images/f/f6/Ender_Pearl_JE3_BE2.png)

### ★★☆☆☆ Mob texture variations (should be distinguishable and recognizable, like red and brown Mooshrooms, but not like horses)
 - Black and white cows
 - Fully brown cows
 - "Duck" Chickens
 
### Lighting:
#### ★★★☆☆ Light emitting entities
#### ★★☆☆☆ Colored light
 - Calculate on a separate thread?
### ★★☆☆☆ Seasons
 - ★★☆☆☆ Can be implemented by cycling through four grass/leave color palettes over time
 - ★★★☆☆ Could possibly affect mobs spawns, like how moon phases affect Slime spawns in Swamps
 - ★★★☆☆ Orange Autumn trees
 - ★☆☆☆☆ Unknown how this should interplay with biomes, e.g. snowy biomes

![A Mongus](https://raw.githubusercontent.com/Vextrove/vextrove_terrain_datapack/main/img/mongus.png "A Mongus")
