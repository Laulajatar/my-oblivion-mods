Sort your Stuff 
Universal Alchemy Sorter and More

A modifcation for Oblivion with patch 1.2.0416 by Laulajatar.
Requires OBSE
Version 1.1



Description
-----------

This mod lets you sort items into every container that is safe for storage and either player-owned or unowned. It is possible to retrieve magic items (ingredients, scrolls, potions and sigil stones) by effect.



How to use
----------

== Storing == 
Point your crosshair at a container and press the B key (configurable in the ini). You will get a menu that lets you store items. 

You can: 
Store Ingredients
Store Food
Store Potions
Store Scrolls
Store Keys
Store Books
Store Soul Gems
Store Sigil Stones
Stack existing items. Let's say you play with MOO and gather Iron Ore, Iron Ingots, Iron Arrowheads, etc. If any of those items are in the container, matching ones from your inventory will be moved over. Or maybe you collect silver spoons and wooden bowls. This works with any item from any mod. The downsides are that you 
a) need to have one item already in the container and 
b) similar items with different IDs (2 different vanilla yarns, cloth, gems etc) will be treated as different items and you need to have one of each. 
It still beats sifting through a few pages of loot every time you return home, in my opinion.
This is probaly most useful if you play with some mods that add certain kinds of items (like crafting materials), as vanilla clutter is a bit useless.


== Taking == 
To take items, sneak and press the B key (or, you know, whatever you set it to) while your crosshair is pointed at a container. This let's you pick up magic items (ingredients, scrolls, potions and sigil stones) by effect. For ingredients, it will only pick up those that match your current Alchemy skill. 
You can display all the food items in the container as well.

The sorter will not handle quest items, equipped items and some special items like nirnroot. It will also not work on owned or respawning containers to prevent you from losing your stuff. Some, but not all, of those restrictions can be lifted in the ini. Other things you can change: 
Whether storing ingredients includes food.
Whether storing books includes notes.
Whether storing books should only store 1 copy of each. 
Whether storing potions includes poisons.
Whether to exlude scripted keys and scripted books. 

People using QZ Easy Menus or something similar can turn on numbered menu points. 

I can exclude some modded items from being handled. You can find a list further down.  
If you come across any item that absolutely needs an exception, let me know, I might (or might not) manage to implement that. That said, I'm more inclined to include mod important items that are not questitem flagged than trashcans. 

This mod should be 100% compatible with all kinds of magic mods, even those that change magic effect names/icons. It reads the current names and icons and adapts my menu. 

If you manage to drop an item into the selection "menu", it will be handed back to you after you've closed the selection menu.
If you manage to drop an item into the show food "menu", it will end up back in the container with the rest of the food you didn't pick up. 
There are only so many bad decisions I am willing to script around.



Known Issues
------------ 

There is a not-so-tiny chance that I messed up somewhere. If any of the selections grabs the wrong item or fails to grab one, or any other bug happens, let me know. 

USING THIS MOD ON SHARED CONTAINERS CAN LEAD TO UNEXPECTED BEHAVIOUR, i.e. containers that allow you to access the same stash from several different locations. 
Those usually override the activation to activate a hidden container, but my mod will interact with the real container. It will look as if your items are lost. 
Sneak and press the hotkey, then select take all items, you will get your stuff back. 

All "Luggages" using one of COBL's scripts are supported (supposedly >.<). Should a mod add its own script, it won't work. (You might have guessed it:) Please inform me if you know of one. 
Vanishing Cabinets of MOO should be supported as well. 
Can't hurt to save before trying.
In general: Think before you store, if you wouldn't use a container normally, don't use my mod to put loot in there.

This mod has no masters. This mod is a free elf. Uhm, I mean, this mod should work with Nehrim. I don't even know if Nehrim has Alchemy. 



Installation
------------

Copy the contents of the archive into the Oblivion\Data Folder. Every mod manager should be able to handle this file. Why am I even writing this? This is the place where all .esp files go, always. You can place the ini file in Data\, oder in Data\ini\ or feed it to hungry mudcrabs*, whatever you prefer. 
*Disclaimer: Feeding it to mudcrabs means you won't be able to change settings.

Activate the .esp in a game launcher of your choice.

This mod ABSOLUTELY needs OBSE. 



Exceptions
----------

Version 1.0:
Mages Guild Key (should be quest item, but anyway)
Nirnroots
Soul Tomatoes
Poisoned Apples
Pinarus' Prize Minotaur Horn (I don't even remember what that is)
Azura's Star
Basic Primary Needs Canteens
Skill Diary Redone Diary
COBL Trashcan and Grinder
COBL Luggages & MOO Vanishing Cabinets



Version History
---------------

Version 1.2
Uhm... I think I fixed something something about unique book storing but I forgot what exactly it was
Note to self: Make notes earlier next time

Version 1.1
Fixed some effects not sorting properly because of a typo
Fixed the OBSE function to remove items leaving behind some ghostly items that could only be detected by scripts

Version 1.0
Initial Release



Footnote
--------
I'm not responsible if your pc blows up after installing this mod, etc etc. 

For a translation: The only script with text is lSortYourShitQuestScript, and the only items that would need to be translated are the ones that include an attribute or skill (i.e. Restore Agility, Absorb Marksman).
