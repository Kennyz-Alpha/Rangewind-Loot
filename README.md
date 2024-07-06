# Rangewind-Loot
	These are my custom loot macros.  I built them as a combination of features from EZLoot and TurboLoot.
	ini files go into a Loot subfolder of the MQ2 macro folder. Example C:\Everquest\MQ2\macros\Loot
	Feel free to ask me questions about them and I will expand out the information.

# Loot.mac
	This is my primary loot macro using the Loot_Main.ini

# Loot_Progression.mac
	Loots based on class and current zone.

# Loot_Me.mac
	Per character macro.  Builds ini in the Loot\Self folder.

# ini Settings Information

	Loot Radius - Distance to look for corpses to loot.  Default:300
	Min Loot Value - Minimum Play value of an item to loot.  Default 1000
	Loot Spells - Loots usable spells you do not have on you or in spellbook.  Default:True
	Default Chat - Location of where to send messages.  Default:rsay
	Loot Count1 - Configurable number for how many of an item to loot. Default:0
	Loot Count2 - Configurable number for how many of an item to loot. Default:0
	Loot Count3 - Configurable number for how many of an item to loot. Default:0
	Loot Count4 - Configurable number for how many of an item to loot. Default:0

	Items get listed under the first character of the item name.  Example
	[A]
	=
	Angryface Familiar (Halloween Reward)=Single
	[B]

	Item tag options

	Keep - Always loot.
	Single - Loot just 1.  Counts items in bags and bank.
	Announce - Calls out the corpse ID to the default chat if the item is found.

	Count1 - References the configured number in settings of how many to loot.
	Count2 - References the configured number in settings of how many to loot.
	Count3 - References the configured number in settings of how many to loot.
	Count4 - References the configured number in settings of how many to loot.
