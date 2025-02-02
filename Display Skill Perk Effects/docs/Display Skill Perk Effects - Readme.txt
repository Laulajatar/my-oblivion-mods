Display Skill Perk Effects

A modifcation for Oblivion with patch 1.2.0416 by Laulajatar.


Description
-----------

This mod takes the idea of Alek's skill perk descriptions to the next level. While the original mod just displayed static texts, this mod was written from scratch to take into account all available game settings. Have a mod that changes sneak damage multiplier or light armor perk bonuses? No problem. In some cases, it will (at least try, lol) to print fitting text: For example if heavy armor encumbrance is 0, it will display "does not encumber", while if a mod changes the multiplier to something like 50%, it will say "encumbers only 50%."

For some mods it also displays additional perks. Mods currently supported are (some effects will only be displayed if enabled in those mods): 

- Maskar's Oblivion Overhaul
  Shows how many animals you can tame with speechcraft
  Shows which weapon and armor you can equip with skill based equipment restrictions
  Shows sneak damage bonus for currently equipped weapon
- Av Latta Magicka 
  Shows all magic school perks
  Shows magic sneak damage for touch and target
  Note: Av Latta Magicka already displays summon limit itself
- De Rerum Dirennis
  Shows the new Alchemy perks
  Note: De Rerum Dirennis already displays potion limit itself
- Oscuro's Oblivion Overhaul
  Shows which locks you can pick with security (this isn't 100% accurate, as the values for locks have a pretty wide range)
- Skill based harvest chance
  Shows modifier for harvest chance if static bonuses are chosen
  Shows double harvest on master if active
- Vanilla Combat Enhanced
  Shows dagger sneak bonus (there was no room for shortsword and sleeping)
  Removes clear % when dynamic calculation of block disarming is active
  All other game settings should (hopefully) work by default, too
- Supreme Magicka
  Shows magic sneak damage bonus 
  Shows potion limits if they differ from vanilla (vanilla: 4/4/4/4/4)
- Bashing Reworked
  Matched the Hand to Hand and Blocking descriptions
- Maskar's Unarmored Skill
  Lists all the effects 
- Fundament Enchanting Addons
  Shows only default values. If you fiddle with FEA's ini, you need to adjust the perks in this mod's ini as well
- Pickpocket Skill Overhaul
  Shows only default values. If you fiddle with Pickpocket Skill Overhaul's ini, you need to adjust the perks in this mod's ini as well
- Real Time Lockpicking by miguick
  Only the default order of perks is supported. If you switch them around, you'll need to use custom text with your ini
- Horse Gameplay Overhaul
  Shows the perks of the Horsemanship skill
- OCraft Crafting Skill
  Shows the perks of the Crafting skill 
  Values are fetched from the ini and update automatically if you change the default settings

  
The mod will initialize itself on game load and then again a few seconds later, to grab the last struggling game settings that are modified via scripts on game start. It will then update the perk texts every 30 seconds or so, to try and avoid having impact on performance, but still cover mods that alter game settings as the character progresses. 

There is an ini file that's not needed for the mod to work, but if this ini file is placed in Oblivion/Data/ini, you can use it to override each perk description. Perhaps you are using a lesser known mod that adds an effect, then you can just add it there. Please check the instruction on top of the ini file, if you want to use it. 
Please note: One line (including text and quotation marks and everything) may not exceed 512 characters. 

I'm kinda open to adding new perks of mods, but chances are higher if a) it's a popular mod, b) the effects are clear and impactful and c) you ask nicely. Even then, I don't have that much time, that's why this mod comes with an ini file, so you can add custom perks yourself, with no modding knowledge. 



Known Issues
------------

If you are not using an interface mod that makes the interface smaller, there will be no room for the text to be displayed. 
I would suggest using Darnified or a variant thereof. If you don't want to use it, Alek uploaded an xml file for the vanilla UI that widens the skill popup window.
https://www.nexusmods.com/oblivion/mods/39135



Installation
------------

Copy the contents of the archive into the Oblivion\Data Folder. *hint hint nudge nudge mod manager*
Activate the .esp in a game launcher of your choice.



Uninstallation
--------------

This mod can be uninstalled at any time. 



Requirements
------------

This mod requires the Oblivion Script Extender (OBSE)
https://github.com/llde/xOBSE/releases



Changelog
---------

Version 1.5
Added support for Horse Gameplay Overhaul
Added support for De Rerum Dirennis while removing the support for Av Latta Magicka changes to Alchemy, which no longer exist
Added support for OCraft Crafting Skill

Version 1.4
Added support for Real Time Lockpicking by miguick with one caveat:
    Only the default order of perks is supported. If you switch them around, you'll need to use custom text with your ini.
Updated to Av Latta 1.19 (Changed destruction perk)
Updated to Maskar's Unarmored skill 1.2
    The FormID of the skill had changed, now it will be recognized again

Version 1.3.3
Adjusted the Master Illusion, Exptert Mysticism and Journeyman Alteration perk to Av Latta 1.16
Added the new Av Latta Alchemy Perks
Added a warning if Av Latta and Skill Based harvest chance are detected together

Version 1.3.2
Changed the expert restoration perk to match av Latta 1.13
Changed the journeyman mysticism perk to match av latta 1.13

Version 1.3.1
Fixed a wrong description for the Av Latta Mysticism Journeyman perk. 

Version 1.3
Updated to Av Latta 1.12
No longer shows potion amount in alchemy skill when av latta is controlling it

Version 1.2
Added support for Pickpocket skill
Added support for Enchanting Skill
Correctly reset all skill mastery descriptions

Version 1.1
Added support for Dialog Tweaks (mercantile investment value)
Added support for Maskar's Unarmored Skill

Version 1.0.1
Fixed a crash when not using skill bashed harvest chance

Version 1.0
Release
