# ValheimPlus Config Options

# Player

### Gameplay
* Modify stamina consumption and regeneration.
* Modify stamina consumption when using tools and weaponry.
* Modify food duration.
* Disable food degradation over time (maintain full benefit for the whole duration).
* Modify carry load.
* Modify auto-pickup range.
* Modify unarmed damage.
* Modify base amount of unarmed damage that is multiplied by your unarmed skill level.
* Modify each skill's experience gain separately by percent.
* Remove screen shakes.
* Tweak/disable death penalty.
* Tweak Rested bonus duration per comfort level.
* Disable the use of portals.
* Modify the Guardian buff duration and cooldown


### Player Hud
* Show skill experience gains in the top left corner.
* Show amount of items in the player's inventory when crafting or building an object.
* Show numerical stamina value below stamina bar.
* Disable red screen flash on receiving damage.
* Display a warning message when attempting to place different crops too close to each other.
* Added hotkey options for forward and backward roll.

**Map**
* Force all players in the server to display their map position.
* Allow all players to share all map exploration with every other player in the server, as long as their map position is displayed (currently players only receive map exploration from other players while they are online).

**Camera**
* Change the player's Field of View.
* Change the maximum zoom-out distance.
* Change the maximum zoom-out distance when on a boat.
* Switch between first person and third person on button press.
* Hotkeys for changing FOV in first person.

**Gathering**
* Modify the amount of resources dropped on destruction of objects (this includes chitin, stone, all types of wood, and minerals).
* Modify the drop chance of resources from destroyed objects.

**Wagon**
* Modify the weight contribution of items placed inside a wagon.
* Modify the base weight of the wagon.

**Fire sources**
* Fire sources retain max fuel once the fuel is added.
* Alternatively, only torches retain max fuel, while other fire sources will continue to consume it.

**Game Difficulty**
* Modify the difficulty multipliers applied to health and damage of enemies based on the number of connected players.
* Modify the range at which the game considers other players to be nearby.
* Add a number of players to the player count for the purpose of difficulty calculation.
* Set the difficulty calculation to a specific player count.


### Inventory
* Modify the inventory behavior so that items will be placed in the first slot rather than the last available slot.
* Modify the size of player inventory and all types of containers, including vehicles:
  * Player inventory can be extended up to 20 x 8.
  * Wood chest inventory can be extended up to 10 x 8.
  * Iron chest inventory can be extended up to 20 x 8.
  * Personal chest inventory can be extended up to 20 x 8.
  * Cart/Wagon chest inventory can be extended up to 30 x 8.
  * Karve chest inventory can be extended up to 30 x 8.
  * Longboat chest inventory can be extended up to 30 x 8.


**Note: As of 0.9.4, player inventory slot configuration is not compatible with Equipment and Quick slots mod**


### Items
* Modify the durability of each item type separately.
* Modify the amount of armor granted by armor pieces.
* Modify the amount of damage blocked by all shields.
* Remove teleport prevention from all items.
* Reduce the weight of all items by percent.
* Modify maximum item stack size by percent.



# Crafting and Production

### Workbench
* Modify Workbench radius.
* Modify the radius at which Workbench attachments can be placed.
* Allow crafting stations to automatically repair all appropriate items in the player's inventory on interaction.

### Kiln and Furnace
* Modify Kiln and Furnace processing speed.
* Modify kiln and Furnace maximum capacity.
* Allow items produced by Kiln and Furnace to be automatically placed in the closest container.

### Beehive 
* Modify Beehive honey production speed.
* Modify Beehive capacity.
* Display time left until next production.
* Allow items produced by Beehive to be automatically placed in the closest container.

### Fermenter
* Modify Fermenter speed.
* Modify Fermenter output amount.
* Display time left until next production.


# Building
* Disable "Invalid Placement" restriction while building.
* Disable deterioration of placeables from weather exposure. 
* Disable deterioration of placeables from water exposure.
* Added a free rotation mode for the default Building Mode.
* Added Advanced Building Mode.
* Added Advanced Editing Mode.
* Modify the structural integrity of placeables.
* Modify the maximum distance you can place objects at.
* Added the ability for the hammer tool to repair all placeables in an area instead of just the targeted placeable.
* Added option for placeables destroyed/dismantled by players to always drop their full material cost, even if built by another player.
* Modify effective radius of comfort placeables.
* Modify Ward structure protection radius.


### Free Rotation Mode for the default Building Mode
* **Video demo: https://imgur.com/xMH7STj.mp4**
* This modifies the default build mode. How it works (all mentioned hotkeys can be modified):
   * Players can rotate the object selected in any direction while in the usual building mode by pressing certain hotkeys. The location of the object can be manipulated with the mouse:
      * ScrollWheel + LeftAlt to rotate by 1 degree on the Y-axis.
      * ScrollWheel + C to rotate by 1 degree on the X-axis.
      * ScrollWheel + Z to rotate by 1 degree on the Z-axis.
   * Use the copy rotation hotkeys to copy the current rotation or apply the same rotation to the next object that is being built.
   * Build the object by clicking.

### Advanced Building Mode
* **Video demo: https://i.imgur.com/ddQCzPy.mp4**
* How it works (all mentioned hotkeys can be modified):
   * Players can freeze the item by pressing the configured key (F1 by default).
   * Players can modify the item position and rotation with the following key combinations:
      * Arrow Up/Down/Left/Right to move the building object in the respective direction.
      * Arrow Up/Down + Control to move the building object up and down.
      * ScrollWheel to rotate the building object on the Y-axis.
      * ScrollWheel + Control to rotate the building object on the X-axis.
      * ScrollWheel + left Alt to rotate the building object on the Z-axis.
      * Numpad plus/minus to either increase or decrease speed, holding SHIFT to raise/lower by 10 instead of 1 (Pressing Shift at any moment in time increases the distance/rotation angle 3 times)
   * Build the object by clicking.
  
**NOTE:**
* *Objects built with this system are not excempt from the structure/support system. Dungeons and other no-build areas are still restricted.*

### Advanced Editing Mode
* **Video demo: https://imgur.com/DMb4ZUv.mp4**
* You cannot be in Build mode (hammer, hoe or terrain tool). How it works: 
   * Players can select the item with the configured key (Numpad0 is default).
   * Players can modify the item position and rotation with the following key combinations:
      * Arrow Up/Down/Left/Right to move the building object in the respective direction.
      * Arrow Up/Down + Control to move the building object up and down.
      * ScrollWheel = rotates the building object on the Y-axis.
      * ScrollWheel + Control to rotate the building object on the X-axis.
      * ScrollWheel + left Alt to rotate the building object on the Z-axis.
      * resetAdvancedEditingMode HotKey resets the position and rotation to the initial values.
      * Numpad plus/minus to either increase or decrease speed, holding SHIFT to raise/lower by 10 instead of 1 (Pressing Shift at any moment in time increases the distance/rotation angle 3 times)
   * Press the confirmPlacementOfAdvancedEditingMode Hotkey to confirm the changes. (press abortAndExitAdvancedEditingMode HotKey to abort editing mode and reset the object).

**NOTE:**
* *Other players will not be able to see the item being moved until the player building the item confirms the placement. Dungeons and other no-build areas are still restricted.* 

### Structural Integrity
* Apply a modifier to the structural integrity of the following materials:
  * Wood
  * Stone
  * Iron
  * Hardwood
* Disable structural integrity entirely (this will cause objects placed mid-air to not break and fall).
* Make anything built by players immune to all damage.
* Make boats invincible to all damage.



# Server
* Remove password requirement for the server.
* Modify the maximum amount of players on a server.
* Modify server data rate in kilobytes.
* Modify number of seconds it takes for items to despawn after being dropped on the ground. (default is 3600 seconds).
   * *Note: Items on ground will retain base game functionality which ensures that drops don't disappear if a player is nearby or there is a "player base" nearby*
* Automatically sync V+ configuration of players joining a server to match the server's configuration.


### Time and Day Manipulation
*This feature is currently disabled*
* Modify total time of day/night cycle.
* Modify speed of time passing at night.
