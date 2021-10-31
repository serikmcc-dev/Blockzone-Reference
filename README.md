# Blockzone

_Blockzone Zombie Horde &amp; Battle Royale Plugin for Minecraft 1.16.5_

```
Minecraft Version: 1.16
Tested Version: 1.16.5
Java Version: Java-SE 1.8
Plugin Version: 5.1.7
```

#### _Foreward_

This is the _README.md_ for the plugin and contains all the instructions and information pertaining to setup, initializing, and deployment of the Blockzone experience within your Minecraft world. This plugin assumes you have __NOT__ built a world on your server yet; if you already have one built, then adding this plugin may cause issues with the experience and gameplay, i.e., some buildings may not be in world borders, some lootboxes may not get registered with the `config`, and so on. It is HIGHLY recommended you start from scratch when utilizing the __Blockzone__ plugin.

------------------------------------------------------------------

## What is Blockzone

__Blockzone__ is a Zombie Horde Survival & Battle Royale plugin that completely turns the tables on what Minecraft is. It gives you the ability to create a world that is hit by the Zombie Apocalypse and leaves it players to either join forces or be the last one standing. With a K/D counter, personal Rucksack and bank, this experience is sure to keep the grind alive for some time! Explore the world and search for places to hide out, lootboxes to replenish stores and find cash, hordes to kill and XP to gain, and of course the PvP element that comes with any apocalypse!

### Features:

1. Battle Lobby
2. World Borders
3. World Protection
4. Spawn Restrictions
5. Weapons and Ammunition
6. Blockzone Bank
7. Lootboxes
8. Blockzone Store
9. Blockzone Player Shop
10. Proximity Chat
11. Rucksacks
12. Daily Bonuses
13. And a __BUNCH__ more

--------------------------------------------------------------------

## Guide Links

__PLEASE__ refer to these links before starting any setup on your Minecraft server! These links will provide you with the necessary information to get the best experience out of Blockzone

- [Config.yml Details & Overview](Guides/Config.md)
- [Commands](Guides/Commands.md)

------------------------------------------------------------------

## Initial Setup Instructions

_Battle Lobby is the REQUIRED first step before doing anything else on your server world for the plugin. DO NOT do anything else until the Battle Lobby has been set!_

It is time to setup your world for the Blockzone experience! Please make sure to follow these instructions to the best of your ability so as to guarantee the best gameplay.

### Battle Lobby Setup --

This setup creates the center and spawn for the world, and engages the World Borders around the area. __THIS COMMAND NEEDS TO BE RUN FIRST!__

##### NOTE:
> Some commands CANNOT be used when outside of the Battle Lobby! Make sure your lobby is clear and defined so players know when they can access the Store or Player Shop

1. Download the _Blockzone_ plugin and add it to your Plugins folder on your server. If a restart is required, please do this now.
2. Adjust the `config.yml` to your liking. __Be sure to only change the values marked in the [Config Details file](Guides/Config.md)__!
3. Join your world and find a location that fits as a center for the battlegrounds and settle on the ground. __Recommended__: Find a wide-open flat area with some mountains, caves, etc. Use the landscape as a guide for the best experience!
4. Use the `/bzset battlelobby` command (found [here](Guides/Commands.md)) to set the spawn & center of your battlegrounds. This will build the World Borders at the specified distance FROM this central location

Once the command has been used, your Battle Lobby will be __20 Blocks__ in all directions from the center you used. Build your Battle Lobby building/compound in this square area so your players will have a safe location to spawn/respawn/teleport to during gameplay.

```
You can NOW start building your Blockzone world buildings, hideouts, and secrets! Be creative and in an 
apocalypse mindset! This plugin is actively being used within my community server, and any individuals 
looking for inspiration are invited to reach out to me for the server address!
```

----------------------------------------------------------------------------------------------------------------------

## Additional Setup Instructions

### Lootbox Setup --

Lootboxes give your players something to search for and award randomly generated in game items, including `Cash Notes`!

1. After selecting/building your structure or site, place a __Chest__ (SINGLE CHEST ONLY) in the lootbox spot.
2. Walk up DIRECTLY to it and stare at the Chest. This ensures the chest is the block receiving the "Lootbox" title.
3. Use the `/bzset lootbox [#]` command (found [here](Guides/Commands.md)) and enter the number you are currently on. I.E., `/bzset lootbox 1`. Dont forget to increment the chests!

After running the command, you will receive a message indicating the lootbox has been set. The plugin will check periodically for contents and add more items to keep loot fresh and stocked. Error message will display if the command was used the incorrect way

---------------------------------------------------------------------------------

## Reference Links

These links will take you through the simple utilization and information that is based on the Blockzone plugin. Use this as a reference if there are any questions about how to use or interact with things in the battlegrounds.

- [Blockzone How-To](Guides/How-To.md)

---------------------------------------------------------------------------------

This plugin was developed by __F4ngb0n3__ and can be used freely in any Minecraft server working with _Bukkit/Spigot_. 

__DO NOT REBUILD, BREAK DOWN, REDISTRIBUTE, OR SELL THIS PLUGIN FOR PERSONAL GAIN__.

That shit is low and pathetic and will be handled with the UTMOST predjudice. If you have ever coded or developed you will understand the hostility. Don't be a waste of space and existence.
