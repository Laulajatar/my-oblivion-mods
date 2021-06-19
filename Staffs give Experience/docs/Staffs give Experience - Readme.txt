Staffs give Experience
A modifcation for Oblivion with patch 1.2.0416 by Laulajatar.
Requires OBSE
Version 1.0

Description
-----------

Casting spells from a staff gives experience to the school of the most expensive part of the enchantment, but only if a target is actually hit with the spell (just like vanilla spells work).   

Any scripted effects will not grant experience. 



Known Issues/Compatibility
--------------------------

Will most likely behave strangely with mods that manipulate how much experience a spell gives depending on spell cost/level:

Works fine with Customizable Magic Progression. 
The updated Supreme Magicka doesn't seem to have this feature anymore.
Haven't looked into Fundament yet. There is a chance it works well because it seems to use event handlers instead of messing with the game settings, but I am currently too tired to understand that code. 

Will not work with any mods that replace use based skill leveling with something else, like Oblivion XP or the similar mode from Ultimate Leveling. 

If you somehow manage to cast multiple times before the projectile actually hits a target, you will not get XP for all of them.



Install
-------

Drop the esp in your Data folder (it's always best to just use a mod manager to install) and check it in your mod manager. Load order doesn't matter. 



Uninstall
---------

Remove the esp.



Version History
---------------

1.0
Initial Release

