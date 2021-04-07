Bookworm
Mark Books as Read & Pick up Skill Books
A modifcation for Oblivion with patch 1.2.0416 by Laulajatar.
Version 1.1.1

Description
-----------

This mod allows you to mark books as read by right clicking on them, either in your inventory or while reading them. A menu will allow you to mark or unmark them as read, by adding [Read] to the start or at the end of the book's name, according to your settings.
[Read] The Lusty Argonian Maid or The Lusty Argonian Maid [Read]

If you want, this mod can mark books as read as soon as you reached the last page, and mark letters, notes, scrolls etc as soon as you open them. You can turn this on individually in the ini. 

You can also turn on the marking of skill books, by adding the [Taught Skill] as suffix. 
The Lusty Argonian Maid [Blade]

Lastly, this mod allows you to pick up skill books without reading them, saving them for later. 
Both, the marking of taught skills and the pickup option will be disabled for a book once you've read it and learned the skill. 

This works with all books, vanilla and mod added. The only exception is the pickup option for scripted & quest object skill books, like the Mythic Dawn Commentaries. Those will not give the option to pick them up, since they usually need to be read for quest progress. 



Known Issues
------------

Some books might have the same content, but exist in different versions. Marking one of those as read will not affect the other versions.  

Since there is no logical reason to mark a skill book as read without having learnt the skill, there is no logic behind which mark goes last when [Read] is set as suffix. Whatever gets handled last will be put last.

Books in the merchant chest of an npc that is no book merchant, but can sell books through the Mercantile perk are not detected. 

All picked up, stolen skill books will show the same icon in the pickup message.
Picking up a stolen skill book will not give a bounty.

This should work for Nehrim as well, as it has no master. 



Conflicts
---------

QZ Easy Menus allows to close menus with a button, per default with right click and space. You should set KeyAlt in lBookworm.ini to a key that is not used by Easy Menus to close menus, for example R. 



Installation
------------

Copy the contents of the archive into the Oblivion\Data Folder.
(For your own sanity, use a mod manager for this).
Activate the .esp in a game launcher of your choice.
Load order doesn't matter.



IMPORTANT Update to 1.1.1
-------------------------
Versions below 1.1.1 had a bug in a script that lead to the .obse co-save being bloated. While it is possible to just update the mod, which will stop the bloat from increasing, a clean save is needed to remove the already existing bloat. To keep the records of your already read books, you can download a plugin in the optional files.

1.) Install lBookwormBackup.esp
2.) Launch the game, follow the instructions.
The instructions will tell you to save in a new slot a few times. This is to make sure you always have a backup save if something goes wrong. Once you've made sure the savegame still works fine after the final step, you can delete them, but honestly, in Oblivion it's always better to have the occasional backup or two. 

If you don't use the mark as read function or don't care, just:

1.) Deactivate lBookworm.esp.
2.) Launch game, ignore warning about missing content.
3.) Save in a new slot.
4.) Close game.
5.) Activate lBookworm.esp.
This will remove all your [Read] marks on books.

Whichever method you chose, you should then continue playing with the "cleaned" savegame. 



Uninstallation
--------------

This mod will not make permanent changes to your savegame, it can be uninstalled at any time. 



Changing the Prefix
-------------------

The [Read] is stored as the name of a misc item, so it can be easily changed. That said, it should be a combination of letters that is unlikely to appear in a normal book title. [r] might still work, while r- would probably kill "Dar-Ma's Diary". Also please note that Oblivion fonts don't have many special characters, so any symbol shenanigans might lead to display bugs/crashes/whatever. You have been warned. 



Requirements
------------

This mod requires the Oblivion Script Extender (OBSE)
https://obse.silverlock.org/



Changelog
---------

Version 1.1.1
Hotfix for .obse savegame bloat
Changed the dummy cell setting so it should no longer be pointlessly merged into the bashed patch

Version 1.1
Added the option to automatically mark books as read when reaching the last page
Added the option to automatically mark notes/letters as read when reading them
Interior cells are now scanned in addition to handling the mouse cursor target
Fixed a bug where the pickup book option didn't like to be disabled
Fixed a bug where a script could have crashed, preventing the picking up of former skill books
It is no longer possible to mark magic scrolls as read
Previously marked magic scrolls will no longer be marked after restarting the game
Revived the script that was supposed to handle the check of books added directly to the player's inventory (quest rewards, scripts, cheats)


Version 1.0
Release 