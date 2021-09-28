**Equiping Weapons** 

This is a DM's, and Players tool to set up weapons that a monster generally does not have. For example, with `!equip`, you can have a goblin with a Flame Tongue! 

**Homebrew svar for Weapons**
```!svar homebrewWeapon
[{
	"fName":"Frostbrand",
	"dice": "2d6 [cold] + 1d8",
	"THDice": "2d6 [cold] + 1d10",
	"damage": "slashing",
	"prof": "Martial",
	"type": "Melee",
	"desc": "Versatile (1d10)"
}]
```

__There is only one required argument ->__ 
`"Weapon Name" | -equip "Weapon Name" | -e "Weapon Name"` is used for selecting the weapon you wish to use. 

**Additional Arguments:**

`-t "Target Name"` is not so much required, as it will default to your current character. __Initiative Sensitive__. 
`-i` Will ignore proficiency requirements and treat the creature you are giving the weapon to as proficient. 
`-b` will add bonus to hit. __Supports Dice__
`-d` will add a bonus to damage. __Supports Dice and Damage__
`-mb` will add a magical bonus, increasing (or decreasing) the attack and damage __Supports Dice and Damage__. 
`-metal | -m` will allow you to pick a metal typeing. (silver is the only important one here.)
`-name` allows you to give the item a name rather than what will be automatically given to it. 
