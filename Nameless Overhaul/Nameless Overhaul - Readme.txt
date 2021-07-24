Nameless Overhaul

==========
ABOUT
==========

There are a lot of other Overhauls out there already and they all do their job well. I've used some of them in my years of playing and I currently love Maskar's Overhaul. In fact, I copied a few ideas from MOO because they were just too good and I didn't want to live without (bandages and imbuement say hi). If you enjoy having new things in your game (mostly enemies and gear) there is no reason to even look at this, because almost everything my overhaul does has been done before.

However, there was a certain thing I just couldn't find. Whenever someone asks for a simple way to remove the bandits in glass armor and disappearing skeletons, I didn't know what to suggest that didn't change too much on top of that. I always imagined a mod that keeps vanilla leveling but just cuts it off at some point, while removing the non combat related nonsense scaling. No more need to reach level 15 to find diamonds. Bandits spawn like normal, but just don't get the rarer gear. You won't be ambushed by a mountain lion on level 1, but you will still find normal wolves on level 20.

Now, to be fully honest, I also do "more". I guess that's the nature of modding. 
I tried to keep the new features out of the way, when possible. Most "tools" have to be bought and explicitly used and no non-vanilla assets were used. 

My main goals were: 

- No OBSE required
- Attempting to stay close to vanilla
- No additional files beside the .esp(s) required
- Vanilla scaling, but no more vanishing rats or endlessly scaling goblins
- Fixing all the instances of having to look up optimal levels like quest rewards
- Adding a few quality of life feature, like crafting lockpicks or unlocking spellmaking



==========
INSTALLATION
==========

The main mod is just one file - lNameless Overhaul.esp from the "00 Core folder".

This file goes into the Oblivion\Data folder and could be enabled in the game launcher. However, the game launcher does not allow you to set your load order (which mod "wins" if you use multiple). Once you plan to use more than one mod you should use a mod manager. Wrye Bash is my recommendation if you don't already have a preference, because the bashed patch is a very important tool and why use two apps if one does the trick. If you are already familiar with Mod Organizer 2, that works well, too!

There are several optional files and patches in the "10 Optional Modules" and "20 DLC Patches" folders. What they do is described at the bottom of the "detailed changes" section. None of those are required, you just need to install them if you plan to use the described features.



==========
DETAILED CHANGES
==========

== Changes to Enemies ==
+ Weaker creatures now won't stop spawning once the player reaches a higher level. You will always encounter rats and skeletons, but on level 1 you still won't see high level creatures
+ Creatures that before never stopped leveling with the player are now capped after a certain level
    Some creatures that naturally would live in packs now can spawn in groups at higher levels
    Affected enemies are rats, wolves, boars, imps and trolls
    At the moment, those group spawns will only happen in the overworld, not in dungeons
+ Wild horses can now spawn in all 5 different vanilla color variants and respawn if killed
    They drop horse meat with the same alchemical effects as venison
+ Goblins living in tribes are now capped as well, but still quite stronger than their tribeless counterparts
+ Most animals now drop both one ingredient (like meat) and one trophy (like pelt) to make hunting a bit more worthwile
+ Hostile NPCs and guards are now level capped, usually between level 20 and 30
    Marauders are stronger than bandits, necromancers are stronger than summoners and vampires are the strongest
    Boss enemies remain uncapped
+ Conjurer and necromancer bosses now can drop enchanted weapons
+ Some creatures and npcs remain unchanged:
    Jailors remain unchanged for better compatibility with the UOP
    Foresters remain unchanged for better compatibility with the UOP
    The guards of the Arcane University remain unchanged for better compatibility with the UOP
    Most named NPCs remain untouched
    The Arena enemies have not been changed
+ Grummites now use grummite bows and the bows' stats were lowered to roughly match the stats of the iron bow
+ All those changes mean the game WILL be easier at higher levels, even if you didn't build your character perfectly. If you're looking for a higher difficulty, this isn't the mod for you
+ Most creature stats are unchanged, their levels just have been capped, usually at about 7 levels after they first spawn. If you're looking for some polished, rebalanced stat overhaul, this isn't the mod for you


== Changes to Loot ==
+ Normal NPC enemies won't spawn with armor better than chainmail and silver (see below) and weapons better than silver
    Boss enemies can still carry (enchanted) gear of higher rarities at appropriate levels
+ Armor/Weapon drops in loot remain largely unchanged
    New armor was added to merchants as well as loot lists
+ Loot that gives no immediate boost in player strength has been unleveled and made fully random (gems, soulgems, pearls, ingredients) 
+ Merchants now carry better gear a up to glass (weapons) and elven/ebony (armor) quality, to make buying gear a real alternative
+ The unused pit armor set has been added to the light armor leveled lists as "Cured Leather Armor" with the same stats as normal leather armor
    This armor drops in both unenchanted and enchanted versions
+ For more variety, the unique Amelion armor set has been added to the heavy armor leveled lists as "Silver Armor" with the same stats as dwemer armor
    This armor drops in both unenchanted and enchanted versions
    The original Amelion armor is still a light armor set and was unchanged
+ Fine Steel weapons now can be found on enemies and in loot, instead of only being available in shops
    Enchanted variants of fine steel weapons were added as well
    The model for the fine steel bow is the same as the model for the normal steel bow
+ Imperial watch armor is now playable. Disclaimer: I don't condone killing the watch to aquire it
+ You can now get a clothing version of the arena rainment that has the same enchantment and model as the light armor version 
    You can recieve it from Owyn and find it in the normal spots
    There is also a clothing version of the champion gear
    The dialogue for those 2 options is unvoiced
+ Previously unavailable enchanted items that existed in the game files were added to the respective leveled lists
+ Previously unsold clothing will now be sold at appropriate merchants
+ A clothing version of the "Bracers" was added to those merchants as well. Doesn't exactly look nice, but fixes the Wrist Irons being the only clothing piece for hands
+ One respawning set of wrist irons has been added to a container somewhere in the IC sewers
+ Moon Sugar now drops in shady locations. Moon Sugar can be refined into Skooma with a Grinder
+ Welkynd stones are now super rare loot in Ayleid chests and normal loot in Ayleid boss chests, to ensure it is always possible to upgrade your quest items
+ Silver and gold veins as well as clams now respawn 
+ Some more worthless loot items have been added, like ruined books or empty flasks, to give a bit more variety when opening the 54th container, looking for calipers
 
 
== Changes to Magic ==
+ The Summon Dremora Lord spell is now available for purchase in the Arcane University, to prevent its effect from becoming unavailable
+ Some spells are available in different magnitudes for easier access to spellmaking: 
    A Novice Water Walking spell can be purchased from Edgar Vautrine & Ungarion
    An Expert Water Walking spell can be purchased from Thaurron
    A Novice Water Breathing spell can be purchased from Alves Uvenim
    An Expert Water Breathing spell can be purchased from Thaurron
    An Apprentice Invisibility spell can be purchased from Edgar Vautrine & Ungarion
    The vanilla Bound Dagger spell can now be purchased from Ungarion, too
+ Costs for Finger of the Mountain have been adjusted to not make it the worst deal ever. It will now cost roughly half as much as a custom made spell would cost, just like Wizard's Fury
+ Once you've aquired either of the two leveled spells, you can buy (or steal) books to upgrade those spells in the First Edition in the Imperial City
    The Ayleid Storm, used to upgrade Finger of the Mountain
    A Furious Wizard, used to upgrade Wizard's Fury
+ The effectiveness of health potions that can be bought or found in loot has been increased (50/100/150 points instead of 20/35/50 points respectively)
 
 
== New Features ==
+ You can find an Arcane Enhancer that can be used to upgrade quest rewards. Put the item in together with a welkynd stone, wait a moment and if available, recieve a new and improved version of your item
    UOP fixes for the leveled rewards have been implemented, to prevent the upgrading of quest rewards giving inconsistent results 
+ Previously missing ingredients and SI ingredients have been added to the archmage's chest. No Nirnroot though, sorry 
+ The robes you recieve after you become archmage now have a powerful (leveled) enchantment. If you'd rather enchant them yourself, a new set of unenchanted archmage robes will be added to the nightstand in the archmage's quarters once per week, if there isn't one already in there
    This change has a failsave in case the quest is overwritten by another mod. Then you will get the enchanted variant on top of your normal quest rewards
+ Gold quest rewards have been unleveled to always give a higher amount of gold. Really, who wants to take out a bandit lair to recieve 20g when you can craft 3 novice potions to get the same
+ Rewards for Dark Brotherhood contracts have been unleveled, too
+ After you've recieved your first set of Dark Seducer/Golden Saint armor, you can buy additional sets that will match your current level from Cutter and Dumag gro-Bonk, respectively
    After you've finished the SI questline, the opposite armor will be available for purchase as well
+ You can donate a not-so-small sum at the Arcane University which will unlock spellmaking and enchanting at each guild hall without being a member. Progressing the MG questline will make the unlock cheaper for each completed quest (recommendations don't count). Once it's done, talk to different people in the guild halls to find the ones that offer this service
+ Certain unique items purchased from a Dark Brotherhood member will no longer become unavailable


== Crafting ==
+ Certain merchants have an Abyssal Soulgem for sale. You can put soul gems in to empty them if you caught a too small soul
    This works for prefilled soulgems, too
    Prefilled soulgems had their prices adjusted to be the equivalent of empty soul gem + soul value, so you can't abuse buying a grand soul gem that's filled with a petty soul for 40 septims and just yeet the soul out
+ Certain alchemists have an Adaptable Grinder for sale. You can use it to grind bones to bonemeal, pearls to dust, wheat grain to flour and moon sugar to skooma
+ Certain general merchants have Average Scissors for sale. You can use them to cut cloth into bandages, which work as a small over-time healing potion, for people who don't want to dabble in alchemy or restoration
    The higher your level, the more powerful the created bandages are
    The bandages are not supposed to make a real difference in combat, but meant to replace the spamming of heals after combat
    If you use dirty linen to create bandages, there is a chance that you'll contract a random disease when using them
    To avoid unnecessary scripts, those bandages are currently treated as potions, i.e. they make potion sounds and are calculated in the potion limit
+ Certain general merchants have an Adamant Hammer for sale. You can use it to make lockpicks from metal clutter like tongs, calipers and shears
+ Yes, those tools all start with A so they are easier to find in the inventory :D


== Other == 
+ Restoration now increases a bit faster and alchemy increases a bit slower
+ Since enchanting is now easier to come by, even for non Mages Guild characters, sigil stones have been overhauled to have some more desirable effects. Effects that did not scale and were common enough on random equipment (for example water walking, night eye) have been removed and several stones now have multiple effects (for exaple fire damage + weakness to fire, fire shield + spell absorption)
+ Simple horse controls for player horses
    The same merchants where you can get the scissors will also sometimes sell an Alluring Carrot
    Activating it when near a player owned horse that you've mounted before will give you the option to give some commands
    You can make the horse follow you
    You can make the horse wait at its current location (if it's the last ridden horse, it will still travel with you when fast traveling)
    You can open its saddle bags for storing loot (the bags have no carry limit) 
    You can release its controls, so it will walk back home if it's not the last ridden horse
+ If the horse is dead, activating the carrot puts all the content of the saddle bags into your inventory
+ This will only work with vanilla player horses
+ You can hotkey the carrot to easily use it without opening your menu.


== Optional == 
An optional esp is available to lessen the levelup requirements. You would get a +5 attribute increase at 5 increased skills rather than 10, while keeping the vanilla leveling system

An optional esp is available to give all magic schools one more starting spell to help out the fledgling mage. This is optional so you can leave it out if you use any magic overhauls that would conflict. Don't use it with Supreme Magicka, SM already adds almost the same start spells. It works with Av Latta Magicka and LAME. I would not recommend using it with Balanced Magic. 
    Alteration recieves a Novice Feather spell that can't be purchased otherwise*
    Conjuration recieves a Bound Dagger spell
    Destruction recieves a Novice Damage Fatigue spell
    Illusion recieves a Novice Charm spell
    Mysticism recieves a Novice Soul Trap spell that can't be purchased otherwise*
    Restoration recieves a Novice Restore Fatigue spell
*Those 2 spells are not sold since every city already sells the apprentice version of these spells. All other start spells are novice versions, so I didn't want to hand out higher level spells


== DLC Patches ==

All of those patches are highly optional. All most of them do is add the leveled rewards from the DLCs to the list of the upgrade tool. If you don't plan to use it, you don't need to install them and you could also install them at a later time if you change your mind. 
If you are using a Bashed Patch, all of them can be safely merged & deactivated.
+ Patch for Battlehorn Castle
    Adds the leveled items from this DLC to the upgrader tool
+ Patch for Mehrunes Dagger
    Adds the leveled items from this DLC to the upgrader tool
+ Patch for Vile Lair
    Adds the leveled items from this DLC to the upgrader tool
+ Patch for Knights of the Nine
    Adds only Umarils sword to the upgrader tool
    All other items can be upgraded in the DLC itself
+ Patch for Horse Armor
    Makes the Alluring Carrot work with armored horses 



==========
Requirements 
==========

This mod requires the latest Oblivion Patch v1.2.0416 with Shivering Isles (for example Steam, GOG)
OBSE is NOT required
KotN and the other small DLCs are not required
It is strongly recommended to use the Unofficial Oblivion Patch and Unofficial Shivering Isles Patch as well, as they fix numerous bugs in the game that might otherwise cause problems. Whenever Nameless Overhaul touches the same records, changes of the UOP have been included. 



==========
Compatibility
==========

This mod changes a lot of lists and is therefore likely to conflict with other mods that do the same. You should probably keep it pretty low in your load order, especially if not using a bashed patch. 

I would not suggest using it with another overhaul - seems pretty pointless anyway, since all overhauls I know of already take care of most of the issues this one tackles. 

Using the bashed patch to solve potential conflicts is highly encouraged.



==========
Known Issues
==========

The carrot will stop working if your horse dies and you use the console to resurrect it. If a horse dies, it is no longer "player owned". Since you are already playing around with the console, use it to fix this (depending on which horse was affected):
Set Horses.OwnAnvilWhite to 1
Set Horses.OwnBravilBay to 1
Set Horses.OwnBrumaPaint to 1
Set Horses.OwnCheydinhalBlack to 1
Set Horses.OwnChorrolChestnut to 1
Set Horses.OwnLeyawiinPaint to 1
Set Horses.OwnSkingradBay to 1
Set Horses.OwnShadowmere to 1

The Arcane Upgrader uses the fixed reward lists from the Unofficial Oblivion Patch, even if you are not using the UOP.



==========
Version History
==========

1.0 
Initial Release
