```statblock  
name: Human Raider  
size: Medium  
type: Humanoid  
subtype: Human  
alignment: Any  
ac: 14  
hp: 22  
hit_dice: 4d8+4  
speed: 30 ft.  
stats: [15, 12, 12, 10, 12, 10]  
  
 
skillsaves:  
- <skill-name>:
- Stealth: 3 
senses: passive Perception 11  
languages: Common  
cr: 1/2  

traits:  
- [<trait-name>, <trait-description>]  
- [Charge, "If the raider moves at least 15 feet straight toward a target and then hits the target with a melee attack on the same turn, the target takes an extra 3 (1d6) damage"]
- [Exploit Opening (3/Day), "When the raider makes an attack, they have advantage on the attack roll."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Handaxe, "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 5 (1d6 + 2) slash ing damage."]
- [Shield Shove, "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4 + 2) bludgeoning damage, and if the target is a Medium or smaller creature, they must succeed on a DC 12 Strength saving throw or be pushed 5 feet away from the raider."]
- ...    
reactions:  
- [<reaction-name>, <reaction-description>] 
- [Splinter Shield, "When the raider is wielding a shield and is hit by an attack made by a creature they can see, the raider gains a +4 bonus to AC against the triggering attack. If this causes the attack to miss, the raider’s shield breaks, and until they get a new shield, their AC is reduced by 2 and they can’t use this reaction or make a Shield Shove attack."]
- ...  
```