## Commands
### `OrderBy-XX`
- `[OrderBy-XX` will rearrange items of the targeted into a gridlike pattern
	- `[OrderBy-Graphic` - Orders the items by their Graphic
	- `[OrderBy-Hue` - Orders the items by their Hue
	- `[OrderBy-Name` - Orders the items by their Name
	- `[OrderBy-Size` - Orders the items by their Size
	- `[OrderBy-Slayer` - Orders weapons by their Slayer
	- `[OrderBy-Weight` - Orders the items by their Weight

!!! tip "Optional Arguments"
	`[OrderBy-Name 15 30` will specify *15 pixels* between columns and *30 pixels* between rows

### `Organize`
- `[Organize` will grab all items in the target bag and sort them into separate bags
	- Descriptions for the possible bags
		- *Armor* - Armor and Quivers
		- *Casting* - Reagents, Spellbooks, Rune stones
		- *Clothing*
		- *Consumables* - Potions, Scrolls
		- *Crafting* -  Resources, Crafting tools
		- *Currency*
		- *Decorative* - Worth ## Gold, Addons
		- *Jewelry* - Jewelry, Gems
		- *Trinkets & Offhands* - Trinkets, Instruments, Torches, Lanterns
		- *Unidentified Items*
		- *Weapons*

??? example "Demonstration"
	![Organize functioning](../assets/gifs/demo-organize.gif)

### `Rename`
- `[Rename` allows players to rename any container that they own

## Gameplay loop
### Crafting
#### Exceptional Bonuses
Exceptionally crafted equipment are minorly magical.

#### Improved Gains
Stop accruing non-basic resources. Higher tier resources offer more chances to gain skill.

#### Multi-crafting
Create a specific number of items in a crafting session with a single click.

??? example "Demonstration"
	![The crafting session gump](../assets/gifs/demo-bulk-crafting.gif)

#### New Crafting Types
- **Slime/Ooze Alchemy** allows you to create slime-based summons or disperse ooze on the floor, which deals damage over time
- **Druidic Alchemy** allows you to craft good-natured utility potions
- **Bonecrafting** allows you to craft armor using bone resources
- **Lapidary** allows you to craft weapons and armor using gem-oriented resources
- **Stitching** allows you to craft weapons and armor using skins of different creatures
- **Witchery/Necrotic Alchemy** allows you to craft evil-natured utility potions

#### Skill Craft List
Players can quickly see which items they can craft for skill gains, and how high the item will take them.

??? example "Demonstration"
	![The skill craft list gump](../assets/gifs/demo-skill-craft-list.gif)

### Dungeoneers
#### Champion Spawns
- Configurable difficulty champion spawns allow a sense of progression and challenge
- Rewards increase as you increase `Spawn Amount` and `Monster Difficulty`
- All kinds of players can enjoy this content (Casual players, group play, or challenging solo play)
- AOE focused templates should focus on increasing `Spawn Amount` (impacts amount of mobs & required kills per level)
- Single-target focused templates should focus on increasing `Monster Difficulty` (impacts health/skills/damage)

??? example "Configuration Demonstration"
	![Champion spawns configuration](../assets/gifs/demo-champion-spawn.gif)

### Gathering
#### Auto-Harvest
Targeting a node once will automatically retarget it until it is emptied.
??? example "Demonstration"
	![Target once to empty nodes](../assets/gifs/demo-auto-harvest.gif)

#### Auto-Separating
Refining a stack of resources will automatically check for skill as-if you separated it and processed it one at a time

#### Auto-Skinning
A skinning knife is the only blade you may use from your backpack.

!!! tip "When equipped, the knife will automatically skin corpses you open."

??? example "Demonstration"
	![Skinning knife on paperdoll auto skins corpses on open](../assets/gifs/demo-auto-skinning.gif)

#### Glistening Ore Veins
Rich deposits of ore may be found randomly spawned throughout the world.

!!! tip "The node may be harvested by using a shovel and targeting it or double-clicking it."

??? example "Demonstration"
	![Harvest a glistening ore vein](../assets/gifs/demo-glistening-ore.gif)

#### Rich Trees
While lumberjacking trees, players may detect a nearby tree that is rich in wood.

!!! tip "The node may be harvested by using an axe and targeting it or double-clicking it."

??? example "Demonstration"
	![Harvest a tree sparkle](../assets/gifs/demo-rich-trees.gif)

## Improved Runebooks
Runebook gump has been rewritten to provide better accessibility and management

??? example "Demonstration"
	![New runebook gump](../assets/gifs/demo-updated-runebook.gif)

## Secondary Skills
All *Gathering* and *Crafting* skills can be raised on your character without impacting your skill cap

!!! warning "Due to their treasurehunting functionality, *Cartography* and *Seafaring* are considered Primary Skills"

??? example "Demonstration"
	![Secondary Skill values don't show up when you mark Show Real](../assets/gifs/demo-secondary-skills.gif)