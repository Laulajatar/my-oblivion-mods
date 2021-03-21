Morrowind-like Leveling

A modifcation for Oblivion with patch 1.2.0416 by Laulajatar.
Requires OBSE
Version 1.0


Description
-----------
This mod gives you the possibility to still get attribute bonuses even after the game prompted you to sleep. You're at 4 points for intelligence when you accidentally hit a levelup? No longer a problem.
It can also handle retroactive health, removing the need to level up endurance as fast as possible.

Another more or less minor feature of this mod is to allow minor and specialization skills to have impact on your level progress. This is off by default but the settings are explained in the ini file.
This doesn't have anything to do with Morrowind, but that's what I was trying to make when I found the other feature, so I left it in.

This mod can be installed without problem on vanilla characters or on a new game. Please make sure to not have outstanding levelups when you install this mod (no sleep symbol on the hud, experience bar to next level not full, you get it.)
If you previously had another leveling mod on that character, please follow the detailed instructions in the install section below.



Install
-------

Copy the contents of the archive into the Oblivion\Data Folder (oder let a mod manager do that job for you). The ini file can be placed in Data\ or in Data\ini.
Make sure you have no outstanding levelups.
Activate the .esp in a game launcher of your choice.

If you had any previous levelling mod installed, first uninstall that mod fully and follow that mod's instructions for uninstalling.
If that mod has no such instructions, you can attempt this: 
Look a your levelup xp bar before uninstalling a previous mod. Let's say you are at 65% to your next level. Make a note of that number and uninstall your other mod. Load the game with no levelingmod, open the console and enter: set iLevelUpSkillCount to 10
Now check your level progress. Is it suddenly 100%? If yes, take your remembered number and divide it by 10 rounded down. So if you remember 65, it becomes 6. Then enter into the console: set setPCMajorSkillUps to *your new number*
Save the game and close it, then install my mod.
If you have any outstanding levelups with your previous levelmod, please go to sleep and level up before following those steps, otherwise weird things might happen that I can't support. 



Uninstall
---------

Close the game, open the ini file, scroll to the end and set lLevelingQuest.Uninstall to 1. 
Open the game, wait till a messagebox pops up telling you the job is done, save the game (preferably in a new slot). 
Close the game and remove this mod. 

If you forgot to do that, you can follow the instructings in the install section as if my mod was that previous leveling mod. 



Version History
---------------
1.0 Initital Release