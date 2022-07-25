**Equipping Armor and Shields**
This is a DM's, and Players tool to set up armor and shields that a monster generally does not have. For example, with `!equip armor`, you can have a goblin in a set of plate mail! 

**Homebrew svar for Armor**
```
!svar homebrewArmor
[{
        "fName":"Dwarvish Plate",
	"armorBonus": "19",
	"dexBonus": "None",
	"strReq":"15",
	"armorType": "Heavy",
	"desc": "This Full set of armor was made by the dwarvish clans of Shea- a mountain village on the border of Schneefällt Provence."
}]
```

__There is only one required argument -> __
`"Armor Name" | -equip "Armor Name" | -e "Armor Name"` is used for selecting the armor you wish to use. 

**Additional Arguments:**
`-t "Target Name"` is not so much required, as it will default to your current character. __Initiative Sensitive__. 
`-i` Will ignore proficiency requirements and treat the creature you are giving the weapon to as proficient. 
`-b` will add a magical bonus to the armor.
`-metal | -m` will allow you to pick a metal typing. (adamantine is the only important one here.)
`-name` allows you to give the item a name rather than what will be automatically given to it.