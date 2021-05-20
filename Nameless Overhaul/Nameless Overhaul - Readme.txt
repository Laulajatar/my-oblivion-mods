Nameless Overhaul

ABOUT

There are a lot of other Overhauls out there already and they all do their job well. I've used some of them in my years of playing and I currently love Maskar's Overhaul. In fact, I copied a few things from MOO because they were just too good and I didn't want to live without (bandages and imbuement say hi). If you enjoy having new things in your game (mostly enemies and gear) there is no reason to even look at this, because almost everything my overhaul does has been done before.

However, when testing mods I wanted an overhaul where I knew exactly what was changed. I wanted basically vanilla progression, but with a cap on things, so I don't run into level 40 goblins or bandits in glass armor. So I made my own. Then I changed a few other things that bothered me, and I added a few things that I just didn't want to leave behind. And now I decided to share it, because why not. 

My main goals were: 

- No OBSE required
- No additional files beside the .esp(s) required
- Vanilla scaling, but no more vanishing rats or endlessly scaling goblins
- Fixing all the instances of having to look up optimal levels like quest rewards
- Adding a few quality of life feature, like crafting lockpicks or updated sigil stones


DETAILED CHANGES

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
+ Hostile NPCs and Guards are now level capped, usually between level 20 and 30
	Marauders are stronger than Bandits, Necromancers are stronger than Summoners and Vampires are the strongest
	Boss Enemies remain uncapped
+ Conjurer and Necromancer bosses now can drop enchanted weapons
+ Some creatures and enemies remain unchanged:
	Jailors remain unchanged for better compatibility with the UOP
    Foresters remain unchanged for better compatibility with the UOP
    The guards of the Arcane University remain unchanged for better compatibility with the UOP
	Most named NPCs remain untouched
	The Arena enemies have not been changed
+ Grummites now use Grummite Bows and the bows' stats were lowered to roughly match the stats of the Iron Bow
+ All those changes mean the game WILL be easier at higher levels, even if you didn't build your character perfectly. If you're looking for a higher difficulty, this isn't the mod for you
+ Most creature stats are unchanged, their levels just have been capped, usually at about 7 levels after they first spawn. If you're looking for some polished, rebalanced stat overhaul, this isn't the mod for you


== Changes to Loot ==
+ Normal NPC enemies won't spawn with armor better than Chainmail and Silver (see below) and Weapons better than Silver
	Boss Enemies can still carry (enchanted) gear of higher rarities at appropriate levels
+ Armor/Weapon drops in loot remain largely unchanged
	New armor was added to merchants as well as loot lists
+ Loot that gives no immediate boost in player strength has been unleveled and made fully random (Gems, Soulgems, Pearls, Ingredients) 
+ Merchants now carry better gear a up to glass (weapons) and elven/ebony (armor) quality, to make buying gear a real alternative
+ The unused Pit Armor set has been added to the Light Armor leveled lists as "Cured Leather Armor" with the same stats as normal Leather Armor
	This armor drops in both unenchanted and enchanted versions
+ For more variety, the unique Amelion Armor set has been added to the Heavy Armor leveled lists as "Silver Armor" with the same stats as Dwemer Armor
	This armor drops in both unenchanted and enchanted versions
	The original Amelion Armor is still a light armor set and was unchanged
+ Fine Steel weapons now can be found on enemies and in loot, instead of only being available in shops
    Enchanted variants of Fine Steel weapons were added as well
    The model for the fine steel bow is the same as the model for the normal steel bow
+ Imperial Watch armor is now playable. Disclaimer: I don't condone killing the watch to aquire it
+ You can now get a clothing version of the Arena Rainment that has the same enchantment and model as the Light Armor version 
	You can recieve it from Owyn and find it in the normal spots
	There is also a clothing version of the champion gear
	The dialogue for those 2 options is unvoiced
+ Previously unavailable enchanted items that existed in the game files were added to the respective leveled lists
+ Previously unsold clothing will now be sold at appropriate merchants
+ A clothing version of the "Bracers" was added to those merchants as well. Doesn't exactly look nice, but fixes the Wrist Irons being the only clothing piece for hands
+ One respawning set of wrist irons has been added to a container somewhere in the IC sewers
+ Moon Sugar now drops in shady locations. Moon Sugar can be refined into Skooma with a Grinder
+ Welkynd Stones are now super rare loot in Ayleid chests and normal loot in Ayleid boss chests, to ensure it is always possible to upgrade your quest items
+ Silver and Gold Veins as well as Clams now respawn 
+ Some more worthless loot items have been added, like ruined books or empty flasks, to give a bit more variety when opening the 54th container, looking for calipers
 
 
== Changes to Magic ==
+ The Summon Dremora Lord spell is now available for Purchase in the Arcane University, to prevent its effect from becoming unavailable
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
+ The effectiveness of Health Potions that can be bought or found in loot has been increased (50/100/150 points instead of 20/35/50 points respectively)
 
 
== New Features ==
+ You can find an Arcane Enhancer that can be used to upgrade quest rewards. Put the item in together with a Welkynd Stone, wait a moment and if available, recieve a new and improved version of your item
	UOP fixes for the leveled rewards have been implemented, to prevent the upgrading of quest rewards giving inconsistent results 
+ Previously missing Ingredients and SI Ingredients have been added to the Archmage's chest. No Nirnroot though, sorry 
+ The robes you recieve after you become Archmage now have a powerful (leveled) enchantment. If you'd rather enchant them yourself, a new set of unenchanted archmage robes will be added to the nightstand in the Archmage's Quarters once per week, if there isn't one already in there
	This change has a failsave in case the quest is overwritten by another mod. Then you will get the enchanted variant on top of your normal quest rewards
+ Gold quest rewards have been unleveled to always give a higher amount of gold. Really, who wants to take out a bandit lair to recieve 20g when you can craft 3 novice potions to get the same
+ Rewards for Dark Brotherhood contracts have been unleveled, too
+ After you've recieved your first set of Dark Seducer/Golden Saint armor, you can buy additional sets that will match your current level from Cutter and Dumag gro-Bonk, respectively
	After you've finished the SI questline, the opposite armor will be available for purchase as well
+ You can donate a not-so-small sum at the Arcane University which will unlock Spellmaking and Enchanting at each guild hall without being a member. Progressing the MG questline will make the unlock cheaper for each completed quest (recommendations don't count). Once it's done, talk to different people in the guild halls to find the ones that offer this service


== Crafting ==
+ Certain merchants have an Abyssal Soulgem for sale. You can put soul gems in to empty them if you caught a too small soul
	This works for prefilled soulgems, too
+ Certain alchemists have an Adaptable Grinder for sale. You can use it to grind bones to bonemeal, pearls to dust, wheat grain to flour and moon sugar to skooma
+ Certain general merchants have Average Scissors for sale. You can use them to cut cloth into bandages, which work as a small over-time healing potion, for people who don't want to dabble in Alchemy or Restoration
	The higher your level, the more powerful the created bandages are
	The bandages are not supposed to make a real difference in combat, but meant to replace the spamming of heals after combat
    If you use dirty linen to create bandages, there is a chance that you'll contract a random disease when using them
    To avoid unnecessary scripts, those bandages are currently treated as potions, i.e. they make potion sounds and are calculated in the potion limit
+ Certain general merchants have an Adamant Hammer for sale. You can use it to make lockpicks from metal clutter like tongs, calipers and shears
+ Yes, those tools all start with A so they are easier to find in the inventory :D


== Other == 
+ Restoration now increases a bit faster and Alchemy increases a bit slower
+ Since enchanting is now easier to come by, even for non Mages Guild characters, Sigil Stones have been overhauled to have some more desirable effects. Effects that did not scale and were common enough on random equipment (for example Water Walking, Night Eye) have been removed and several stones now have multiple effects (for exaple Fire Damage + Weakness to Fire, Fire Shield + Spell Absorption)
+ Simple horse controls for vanilla player horses
    The same merchants where you can get the scissors will also sometimes sell an Alluring Carrot
    Activating it when near a player owned horse that you've mounted before will give you the option to give some commands
    You can make the horse follow you
    You can make the horse wait at its current location (if it's the last ridden horse, it will still travel with you when fast traveling)
    You can open its saddle bags for storing loot (the bags have no carry limit) 
    You can release its controls, so it will walk back home if it's not the last ridden horse
+ This currently doesn't work for armored horses, a patch will be made if it turns out functional
+ This might not work if you have/had another mod that edits the horses. Nothing bad should happen, the carrot might just fail to recognize that a horse belongs to you.
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

All of those patches are highly optional. All most of them do is add the leveled rewards from the DLCs to the list of the upgrade tool. If you don't plan to use it, you don't need to install them and you could also install them at a later time if you change your min. 
If you are using a Bashed Patch, all of them can be safely merged & deactivated.
+ Patch for Battlehorn Castle
+ Patch for Mehrunes Dagger
+ Patch for Vile Lair
+ Patch for Knights of the Nine
    Adds only Umarils sword to the upgrader tool
    All other items can be upgraded in the DLC itself
+ Patch for Horse Armor
    Makes the Alluring Carrot work with armored horses as well

	

== Requirements == 
This mod requires the latest Oblivion Patch v1.2.0416 with Shivering Isles (for example GotY edition, Steam, GOG)
OBSE is NOT required
KotN and the other small DLCs are not required
It is strongly recommended to use the Unofficial Oblivion Patch and Unofficial Shivering Isles Patch as well, as they fix numerous bugs in the game that might otherwise cause problems. Whenever Nameless Overhaul touches the same records, changes of the UOP have been included. 


==========================================

NOTES 

==========================================
		
The Attuned Soulgem is used to empty soulgems if you caught a too small soul and want to try again. Put the soul gems you want to empty in and close the container and your inventory. After a moment you will recieve your emtpy soul gems.

The Scisssors are used to cut Cloth into Bandages. It works with "Cloth" and "Folded Cloth" but not with any other kind of fabric based products like clothes. To use the Scissors, put the Cloth you want to cut up in and close the container and your inventory. After a moment you will recieve your Bandages. You can find them in the potion menu.

The Grinder is used to grind Bones into Bone Meal as well as Gems and Pearls into dust. The amount of dust you get depends on the quality of the item that you put in. To use the Grinder, put the items you want to grind and close the container and your inventory. After a moment you will recieve your dust. 

The Arcane Enhancer is used to upgrade leveled quest rewards. Put the item you want to upgrade in along with a Welkynd Stone and close the container and your inventory. If you meet the level requirements for the next best item, you'll recieve an enhanced version, otherwise you will get your items back. If you put several items and Weklynd Stones in, you can upgrade in bulk.

1 50 
2 45 90
3 40 120
4 35 140
5 30 150


Dried Flowers
Empty Potion Bottle
Empty Poison Bottle
Brick
Stamper
Honey
Blue Cheese Wedge
Orange Cheese Wedge
Creamy Cheese Wedge
Yellow Cheese Wedge
PIe?
ms06logemmamay
octavo01-3
note01
se04chaliceofreversal
lowerclass/sedementia/shirt_gnd.nif and dark, with robe hood icons


Clutter\Books\Octavo02.NIF
Clutter\IconBook9.dds
Clutter\Books\Octavo01.NIF
Clutter\IconBook7.dds
Clutter\Books\Octavo03.NIF
Clutter\IconBook8.dds

Clutter\Potions\PotionPoison.NIF
Clutter\Potions\IconPotionPoison01.dds
Clutter\Potions\Potion01.NIF
Clutter\Potions\IconPotion01.dds

Architecture\StoneWall\StoneWallStone02.NIF
Clutter\IconBrick02.dds

Clutter\SoulGemBlack.NIF
Clutter\Soulgems\SoulGemBlack01.dds


LaulaHorseTokenReturn
LaulaSaddlebagsLeyawiinRef
LaulaHorseHomeAnvilRef

Archmage Hood
 1	5 Magicka, 1 Absorb
 5	10 Magicka, 2 Absorb
10  20 Magicka, 4 Absorb
15  30 Magicka, 6 Absorb
20  40 Magicka, 8 Absorb
25  50 Magicka, 10 Absorb

Archmage Robe
 1	10 Magicka, 2 Absorb, 5 Resist Wep
 5	20 Magicka, 4 Absorb, 7 Resist Wep 
10	40 Magicka, 8 Absorb, 9 Resist Wep
15  60 Magicka, 12 Absorb, 11 Resist Wep
20  80 Magicka, 16 Absorb, 13 Resist Wep
25  100 Magicka, 20 Absorb, 15 Resist Wep

https://cs.elderscrolls.com/index.php?title=FMagicLevelMagnitudeMult
https://cs.elderscrolls.com/index.php?title=FDamageWeaponMult
https://cs.elderscrolls.com/index.php?title=FArrowSpeedMult
https://cs.elderscrolls.com/index.php?title=IArrowInventoryChance
https://cs.elderscrolls.com/index.php?title=ILowLevelNPCMaxLevel

AbTroll "Troll Abilities" [SPEL:0002B545]
AbTrollEasy "Troll Abilities" [SPEL:000CA105]
AbTrollHard "Troll Abilities" [SPEL:000CA106]
321


LL0LootMicroTreasure15 [LVLI:0003FAEE]
LL1LootSoulGems50 [LVLI:0006EEF9]
LL2LootJewelryMagic50 [LVLI:000872A2]
LL2LootPotionsMagic50 [LVLI:000A6F56]


goblin 1
skirmish 4
berserk 8 
shaman 13-20
warlord 18-25

goblin 10
others 16
shaman 22
warlord 28
		
Pearl 		Water Breathing	Water Walking	Dispel			Cure Disease	2
Ruby		Res Health 		Dmg Health 		Fortify Health 	Fire Shield		10
Topaz		Light 			Chameleon		Silence 		Paralyze		5
Emerald		Res Fatigue		Dmg Fatigue		Fortify Fatigue Shock Shield	20
Sapphire	Res Mana		Dmg Mana		Fortify Mana 	Frost Shield	15
Diamond		Fortify Luck	Shield			Reflect Dmg		Reflect Spell	25

Bear 	Pelt	Meat (Boar Meat )
Boar 	Meat	Pelt (Bear Pelt)
Deer 	Meat	Hide (Lion Pelt)
Dog  	Nothing	Pelt (Wolf Pelt)
Lion 	Pelt	Heart (Human Heart )
Crab 	Meat	Shell Piece (Gnarl Bark)
Clam	Pearl	Meat (Crab Meat )
Rat  	Meat	Incisors (Ogre Teeth)
Wolf 	Pelt 	Fang (Hound Tooth )
Fish 	Scales 	Fins (Scalon Fin)

Anvil Spell Thaurron
Anvil Enchant Marc Gulitte
Bravil Spell Delphine Jend
Bravil Enchant Ita Rienus
Bruma Spell Selena Orania
Bruma Enchant Volanaro
Cheydinhal Spell Trayvond the Redguard
Cheydinhal Enchant Uurwen
Chorrol Spell Alberic Litte
Chorrol Enchant Contumeliorus Florius
Leyawiin Spell Alves Uvenim
Leyawiin Enchant Agata
Skingrad Spell Druja
Skingrad Enchant Vigge the Cautious



Bandits around lvl 23
Marauders around lvl 28
Vampires around lvl 32
Conjurers around lvl 23
Necromancers around lvl 28
Guards lvl 30
Palace Guards lvl 35

LaulaUOPForesterDeerFixScript [SCPT:030084A8]
LaulaUOPImperialLegionForesterFixScript [SCPT:030084A9]
LaulaUOPDeathAnimFix [SCPT:030084AA]



scn UOPForesterDeerFixScript

; Works with the Forester fix script which removes Venison from deer so that other foresters don't target the same deer
; This script puts the Venison back when the deer dies so the first Forester can retrieve it
; Copied from the Unofficial Oblivion Patch to prevent conflicts (or rather, the loss of this fix) when the user is not using the patch

Begin OnDeath
	RemoveItem Venison 2
	AddItem Venison 1
End

scn UOPImperialLegionForesterFixScript

; Stops Imperial Legion Foresters from fighting each other if there's a deer in the area
; Copied from the Unofficial Oblivion Patch to prevent conflicts (or rather, the loss of this fix) when the user is not using the patch

ref target

Begin OnStartCombat

	PayFineThief
	set target to GetCombatTarget
	if target != player
		target.RemoveItem Venison 99
	endif

End

Begin GameMode

	if IsInCombat == 1
		set target to GetCombatTarget
		if target.IsGuard == 1
			target.SCAOnActor
			StopCombat
			EVP
		endif
	endif


End



scn UOPDeathAnimFix

; Copied from the Unofficial Oblivion Patch to prevent conflicts (or rather, the loss of this fix) when the user is not using the patch

Float Timer
Short Dead

Begin GameMode
	if Dead
		if Timer > 0
			set Timer to Timer - GetSecondsPassed
		else
			if isAnimPlaying
				PlayGroup Death 1
				set Timer to 4
			else
				set Dead to 0
			endif
		endif
	endif
End

Begin OnDeath
set Dead to 1
set Timer to 4
End


LaulaHeavyMithrilBoots "Heavy Mithril Boots" [ARMO:030076F0]
LaulaEnchHeavyMithrilBootsElements "Boots of the Elements" [ARMO:030076F6]
LaulaEnchHeavyMithrilBootsFeather "Boots of Feather" [ARMO:030076F7]

LaulaHeavyMithrilCuirass "Heavy Mithril Cuirass" [ARMO:030076F1]
LaulaEnchHeavyMithrilCuirassFortHeavyArmor "Soldier's Cuirass" [ARMO:030076F9]
LaulaEnchHeavyMithrilCuirassResistNormalWeapons "Bladebreaker Cuirass" [ARMO:030076F8]

LaulaHeavyMithrilGauntlets "Heavy Mithril Gauntlets" [ARMO:030076F2]
LaulaEnchHeavyMithrilGauntletsFortArmorer "Gauntles of the Forge" [ARMO:030076FA]
LaulaEnchHeavyMithrilGauntletsResistFrost "Northern Gauntlets" [ARMO:030076FB]

LaulaHeavyMithrilGreaves "Heavy Mithril Greaves" [ARMO:030076F3]
LaulaEnchHeavyMithrilGreavesResistFire "Greaves of Oblivion" [ARMO:030076FD]
LaulaEnchHeavyMithrilGreavesSpellAbsorption "Magebane Greaves" [ARMO:030076FC]

LaulaHeavyMithrilHelmet "Heavy Mithril Helmet" [ARMO:030076F4]
LaulaEnchHeavyMithrilHelmetDetectLife "Tracker's Helmet" [ARMO:030076FE]
LaulaEnchHeavyMithrilHelmetFortMagicka "Helmet of the Mage" [ARMO:030076FF]

LaulaHeavyMithrilShield "Heavy Mithril Shield" [ARMO:030076F5]
LaulaEnchHeavyMithrilShieldFortBlock "Shield of Protection" [ARMO:03007700]
LaulaEnchHeavyMithrilShieldLight "Shield of the Sun" [ARMO:03007701]


LaulaPitBoots "Cured Leather Boots" [ARMO:03000ED3]
LaulaEnchLeatherBootsWaterwalking "Seawalking Boots" [ARMO:03001003]
LaulaEnchLeatherBootsOlympian "Boots of the Cat" [ARMO:03001002]

LaulaPitCuirass "Cured Leather Cuirass" [ARMO:03000ED4]
LaulaEnchLeatherCuirassCameleon "Cuirass of Shadows" [ARMO:03001004]
LaulaEnchLeatherCuirassResistNormalWeapons "Swordbane Cuirass" [ARMO:03001005]

LaulaPitGauntlets "Cured Leather Gauntlets" [ARMO:03000ED5]
LaulaEnchLeatherGauntletsFortMarksman "Marksman Gauntlets" [ARMO:03001007]
LaulaEnchLeatherGauntletsBattlemage "Gauntlets of the Spell~sword" [ARMO:03001006]

LaulaPitGreaves "Cured Leather Greaves" [ARMO:03000ED6]
LaulaEnchLeatherGreavesFortAcrobatics "Greaves of Acrobatics" [ARMO:03001008]
LaulaEnchLeatherGreavesFortLightArmor "Greaves of Talent" [ARMO:03001009]

LaulaPitHelmet "Cured Leather Helmet" [ARMO:03000ED7]
LaulaEnchLeatherHelmetDetectLife "Helmet of the Tracker" [ARMO:0300100A]
LaulaEnchLeatherHelmetResistMagic "Magebane Helmet" [ARMO:0300100B]



Arrow6Glass "Glass Arrow" [AMMO:00022BE1]
Arrow7Ebony "Ebony Arrow" [AMMO:0001EFD5]


Lvl	Str	Dur	Sum		
1	1	50	50		
10	2	45	90	40	-5
20	3	40	120	30	-5
30	4	35	140	20	-5
40+	5	30	150	10	-5
