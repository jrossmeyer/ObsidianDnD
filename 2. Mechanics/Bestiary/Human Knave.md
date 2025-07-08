```statblock  
name: Human Knave  
size: Medium  
type: Humanoid  
subtype: Human  
alignment: Any  
ac: 16  
hp: 60  
hit_dice: 8d8 + 24  
speed: 30 ft.  
stats: [18, 10, 16, 10, 12, 10]  
  
 
skillsaves:  
- <skill-name>:
- Intimidation: 4
- Perception: 3
senses: passive Perception 13  
languages: Common  
cr: 3  

traits:  
- [<trait-name>, <trait-description>]  
- [Exploit Opening (3/Day), "When the raider makes an attack, they have advantage on the attack roll."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Multiattack, "The knave makes two Morningstar or two Javelin attacks. They can replace one attack with a Shield Bash attack."]
- [Morningstar, "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) piercing damage, or 13 (2d8 + 4) piercing damage if the target is prone."]
- [Shield Bash, "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4 + 4) bludgeoning damage, and if the target is a Medium or smaller creature, they must succeed on a DC 14 Strength saving throw or be knocked prone."]
- [Javelin, "Ranged Weapon Attack: +6 to hit, range 30/120 ft., one target. Hit: 7 (1d6 + 4) piercing damage."]
- [Stay Down(BA), "The knave kicks one prone creature within 5 feet of them. The target must succeed on a DC 14 Constitution saving throw or their speed is reduced to 0 until the end of their next turn."]
- ...    
reactions:  
- [<reaction-name>, <reaction-description>] 

- ...  
```