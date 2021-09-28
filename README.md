# Let's get to `!equip`ing! 
This is a workshop on Avrae's Dashobard.
You can PM me if you have any questions, but I prefer you use the [GitHub](https://github.com/Adalbar3333/Lets_get_to_Equiping/) to report an issue.

## Basic Information 
This alias is a tool for DM's and Players alike to add Weapons and Armor to their characters and monsters. <br>
Say your character grabs an Orc's Greataxe, but does not have one in their inventory, well now you can add it.<br>
Say you want to have a goblin in magical full plate wielding a Glaive, well now you can! 

### `!equip`
#### Equiping Weapons
This is a DM's, and Players tool to set up weapons that a monster generally does not have. For example, with !equip, you can have a goblin with a Flame Tongue!
#### Homebrew svar for Weapons
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
#### There is only one required argument ->
##### "Weapon Name" | -equip "Weapon Name" | -e "Weapon Name" is used for selecting the weapon you wish to use.
#### Additional Arguments:
-t "Target Name" is not so much required, as it will default to your current character. __Initiative Sensitive__.<br>
-i Will ignore proficiency requirements and treat the creature you are giving the weapon to as proficient.<br>
-b will add bonus to hit. __Supports Dice__ <br>
-d will add a bonus to damage. __Supports Dice and Damage__ <br>
-mb will add a magical bonus, increasing (or decreasing) the attack and damage Supports Dice and Damage. <br>
-metal | -m will allow you to pick a metal typeing. (silver is the only important one here.) <br>
-name allows you to give the item a name rather than what will be automatically given to it. <br>
