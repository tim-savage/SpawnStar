### This repository has been moved to the WinterhavenMC organization

https://github.com/winterhavenmc/SpawnStar

# SpawnStar

A configurable item that serves as a physical replacement for the /spawn command. In my survival world, I felt that the /spawn command was too easy. But my players really wanted to be able to return to spawn easily. So I made this plugin as a compromise. Now, players need to buy SpawnStars from shops before venturing out into the wilderness if they want to be able to teleport back to the world spawn. Also, players would sometimes get stuck in the nether, so I made a configurable option to allow a SpawnStar to return the player to the overworld spawn from the nether or end world.

# Features

*   A fully configurable item that returns a player to spawn when used. Default item is a netherstar, but can be changed to any item.
*   Customizable display name and lore.
*   Option to teleport back to overworld from nether or the end.
*   Configurable cool down period.
*   Configurable warm up period, with optional particle effects during warm up.
*   Individually configurable options to cancel teleport during warmup on damage, movement, or block interaction.
*   Configurable option to remove item from inventory on use, after successful teleport, or never.
*   Configurable option to prevent using SpawnStar items in crafting recipes.
*   Configurable option to require shift-click to use.
*   Uses MultiVerse world aliases in messages, if installed.
*   Uses MultiVerse world spawn location, if installed. (So players will be looking in the right direction on respawn.)
*   Configurable per message repeat delay (message cooldown) where appropriate.
*   Customizable language support.

# Commands

Command | Description
------- | -----------
`/spawnstar reload` | reloads the configuration without needing to restart the server.
`/spawnstar status` | displays configuration settings.
`/spawnstar give <playername> [quantity]` | allows admins or others with permission to give SpawnStars directly to players.

# Permissions

Permission | Description | Default
---------- | ----------- | -------
`spawnstar.use` | gives a player the ability to use a SpawnStar. | true
`spawnstar.admin` | gives a player access to the following admin commands: | op
`spawnstar.give` | allows players to give SpawnStar items to other players. | op
`spawnstar.reload` | allows reloading of configuration files. | op
`spawnstar.status` | allows viewing configuration settings. | op
