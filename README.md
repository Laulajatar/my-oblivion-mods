# This is where I would put my mods in progress

If I had the patience to actually work on anything.    

If you actually happen to find this, it's "use at your own risk" territory. Stuff might be in all stages from "raw idea" to "fully working but not willing to deal with people and release it". I'll try to mark known problems here, but be warned. 


## Ambient Dungeons

Changes the ambient light of a couple of Ayleid ruins to be slightly tinted. It's not randomized, so all interiors belonging to one ruin will have the same color. Recommended to import C.lights and NoMerge the rest in Wrye Bash. No issues. 


## Birthsigns

Just a personal rebalance of birthsigns/race abilities, loosely inspired by bgBalance. 


## Bookworm

Update of the Bookworm mod, using ConScribe to make it possible to sync the read progress across several played characters. No known issues, but as I don't play mutiple characters (or, uh, play at all tbh) it's not tested. 


## Calm Water

Some pathetic attempt at more clear and transparent water, some very clear mountain lakes, some tinted interior waters as well as green swamp water. Not compatible with UL. As with all water transparencies, at the ocean (or other huge water bodies) it will look weird outside the rendered cells. 

## CTAddPose Custom ESP

To be used with this tutorial [Making your own one-mod pose collection](http://www.shrine-of-kynareth.de/making-your-own-one-mod-pose-collection).


## Dynamically Adjusted Darkness

Uses a script (similar to the one in MOO) that changes the darkness of nights. Could also be used to make them brighter, but too low source values (example: NAO) result in a weird tint. 
Can be disabled for SI and Tamriel independently. The SI check uses GetPlayerInSEWorld, so just porting there to test won't work and everytime the value is not set, the script will assume the player is in Tamriel. 


## Fog of War

Small plugin that adds a fog distance of 8000 to all weathers. 
Was a request on reddit. For players who don't like how the lod looks and basically prefer a smaller draw distance. 


## Morrowind-like Leveling

Allows you to keep increasing skills for attribute bonuses before going to sleep, even after the game told you you are ready to level up. Can optionally allow minor and spec skills to have impact on leveling, too. Should be functional on new game, will react unpredictable if adding to a running game with outstanding levelups (just don't), might react unpredictable if leveling in tutorial too much (gotta check how it behaves at the gate, perhaps just suspend until player exists). 


## Nameless Overhaul

Close to vanilla overhaul that keeps a lot of vanilla scaling but puts an end to endless leveling enenmies and bandits in glass armor. Includes some quality of life features like artifact upgrading and simple bandage/lockpick crafting. 
Issues: DLC patches missing for upgrader, balancing untested on level 15+. Lockpicks are too easy to get with crafting. Pondering making the bandages a misc item instead of a potion, that summons a spellcaster only if out of combat. 
Plan for DLC patches was to take one of the prepared quest scripts, edit it in a patch for that DLC to check for those quest objects. Patch loaded > Script will run. Patch not loaded > Script will just move on to the next. Just this way to preserve the non-obse requirement.


## New Familiars

Adds a spell that summons a permanent familiar with a ghostly look. It can be leveled up by giving it a Welkynd Stone, not higher than player level as well as Mysticism/2, whatever is lowest. A lvl 14 player with Mysticism 20 could have a lvl 10 Familiar. Will sometimes find items when idle.
The water walking ability sometimes bugs out and generally, the ghostly effect bugs out when walking on water. Probably engine things.   
Plans: Block some of the forms off till later (lion and wisp and stuff are probably a bit too op early on.) Replace Imp with something? Because it keeps getting stuck. possibly elytra or baliwog or custom creature. Add some script so the buggers don't get stuck behind doors (or does it perhaps need some higer process setting).


## New Gems

Adds 7 new gems to the game, and gemdust for all 12 gems (7 + 5 vanilla) as well as pearl dust.     
The new gems are amethyst (purple), spinel (pink), aquamarine (light blue), onyx (black), peridot (light green), citrine (yellow) and tourmaline (cyan). The dust can be used for alchemy. Currently those gems are only found in the testinghall.     
Plans: Add the gems to leveled lists (while making them unleveled), and adding some way to grind them to dust (preferably without relying on COBL).


## Respawning Ayleid Stones

Replaces Ayleid stones on pickup with a new one that will respawn in (ini set) intervals. No known issues. Since it uses PlaceAtMe, check uninstall instructions if you ever want to uninstall. 


## Shivering Weather mixed up

Takes a few of the unused vanilla shivering isles weathers and puts them into the rotation.
Mania/Dementia weather isn't clearly divided anymore, chances for the corresponding weathers are higher in the right region, but all weathers can happen everywhere.    
Nights are roughly 50% darker.


## Traveler's Tent

This mod has been released on the nexus.   
This version is adding some further development/fixes without proper time for testing. Currently:    
- Replaces Moveto command on tent interaction with a real door. 
- Fixes the local map showing dummy interiors I used for decorating.
- Added the scripted spell failsafe from this [article](https://www.nexusmods.com/oblivion/articles/44458/) to the mark companion spell.
