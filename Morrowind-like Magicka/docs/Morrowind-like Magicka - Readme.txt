Description
-----------

This was a request on reddit. I couldn't find anything matching the description, so I made it. 
This mod stops Magicka regeneration. You'll have to rest, wait or use potions/absorb to regain Magicka, like in Morrowind. 
(Atronachs still don't get Magicka by resting or sleeping.)

If you only want to restore Magicka while really sleeping in a bed, check the ini file for settings. 
Other than in Morrowind it is not possible to "sleep" in the Wilderness without a bed, though. I'd suggest a mod like Maskar's Camping.

NEW in 2.0: Full Morrowind Mode! 
Turn on this mode in the ini to make Magicka regeneration based purely on Willpower (optional: Intelligence), not on your max. Magicka pool - in vanilla, your Willpower determines how long it takes for your whole pool to regenerate, no matter if its 50 or 500. 
You can also use the Willpower-based regeneration during gameplay, not only on sleep/wait. Check the ini file. 

If you want to fully heal on wait, but still use Willpower based regeneration during gameplay, you can play around with the values a bit. Setting the multiplier for Willpower super high and the GameModeMult very low (roughly multiplying ReturnWil * 100 and dividing GameModeMult / 100) will achieve that result. 
For example: 
set lMLMReturnWil to 15
set lMLMGameModeMult to 0.05

Requires OBSE.



Install
-------

Drop file in Data folder (or let a mod manager do that job for you), check esp in whatever mod manager you use. 
Since 2.0, there is also an ini file, which can be put in Data or Data\ini. It isn't necessary for the mod to work, only to change settings. 

Make sure it loads after other mods that modify fMagickaReturnBase & fMagickaReturnMult (probably overhauls and magic overhauls). It does not edit anything else but those two values, so loading it late should be pretty safe. If any of your mods (like Supreme Magicka) edit those values with a script, they should be set to 0 in their respective inis.

For Supreme Magicka, this means:
SetGS fMagickaReturnBase 0
SetGS fMagickaReturnMult 0
set zzSMConfigurationQuest.MagickaCombatBase to -1



Uninstall
---------

Uncheck and delete file(s). 



Version History
---------------
2.2 Morrowind mode with GameMode regeneration will now correctly take fast travel time into account
    Cleared up a few unneeded calls to the calculation function
	NPCs will now regenerate magicka when you wait, even in Morrowind mode
2.1 Takes changes of Wil/Int into account
2.0 Added Full Morrowind Mode
1.1 Added the option to disable regenerating Magicka while not sleeping in a bed.
1.0 Initital Release