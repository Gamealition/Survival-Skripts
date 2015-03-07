These are the commands and events that power the DEMEANOR ERADICATION & REHABILITATION PENITENTIARY INSTITUTE (hereforth DERPI) system. It handles moderator commands and processes for committing and releasing a player to the DERPI quarry. To get this system working, the following is required:

* [Skript](http://njol.ch/projects/skript/)
* A world named "world_derpi", preferably administered by Multiverse with the following traits:
  * All stone biome generation (handled this with [Terrain Control](http://dev.bukkit.org/bukkit-plugins/terrain-control/)
  * A shack for putting the Freedom, Cobblestone, Tool and Food signs
  * PvP enabled, no weather or mob and animal spawns
* A permissions group called `inmate` which inherits from no defaults and has effective permissions denied and the `derpi.inmate` node
* Any moderator or admin permission group should have the node `derpi.moderator`
