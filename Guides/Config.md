# Config Details & Overview

__Blockzone__ uses Color Codes for prettier messages and displays! These color codes are prefixed with the `&` symbol and followed by a corresponding number; i.e., `&2` displays text following it as __GREEN__ and all color codes can be referenced by following [this link](https://minecraft.fandom.com/wiki/Formatting_codes).

_IT SHOWS A DIFFERENT SYMBOL, BUT MAKE SURE YOU USE THE `&` SYMBOL!_

Variable | Default | Changeable | Description
-------- | ------- | ---------- | -----------
prefix | "&[4BLOCKZONE]&f >>" | Yes | Prefix to any server based message sent to a player
w-title | "&d{PLAYER}" | Yes | Default __Welcome__ title that is deisplayed when a player joins the server for the firs time. Defaults to a colored display of the joining player name.
w-subtitle | "&aWelcome to &4Blockzone&f!" | Yes | Default subtitle message displayed with the `w-title`
wb-title | "&d{PLAYER}" | Yes |Default title to exisitng players joining the server again
wb-subtitle | "&aWelcome Back!" | Yes | Default Welcome Back subtitle displayed with `wb-title`
ready-title | "&aReady! | Yes | Default messaged displayed when player prepares for deployment into active battle world from the lobby
ready-subtitle | "&6Dropping in {TIME} seconds" | Yes | Default subtitle displayed with the `ready-title`. {TIME} is defined within the config file.
battleground-world-name | (empty) | No | This will default to the world that is set as such on your server, Changing this can cause issues.
battleground-size | 500.0 | Yes | This is the World Borders distance setting that is taken from the Battle Lobby center location. This will determine how much area is inside your battleground
border-distance | 250 | Yes | Sets the distance from center that a player will be dropped within the borders of the battleground.
active-players | (empty) | No | Stores all player data for players that have joined the server. DO NOT ALTER!
player-rucksacks | (empty) | No | Stores all of the items a player places in their personal rucksack. Changing this can cause data loss and issues with the plugin.
battle-lobby | (empty) | No | Saves the player location as `center` and builds the World Borders around this location. DO NOT ALTER! Use in-game commands to change!
drop-timer | 15 | Yes | Time in seconds before player is randomly teleported into the active battleground.
loot-box-spots | (empty) | No | Stores all of the lootboxes that have been setup in the world. Mainly used as re-locater. DO NOT ALTER!
shop-items | (empty) | No | Saves all of the items placed for sale by players and is used within the __Blockzone Player Shop__. DO NOT ALTER!
