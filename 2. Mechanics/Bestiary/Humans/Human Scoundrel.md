```statblock  
name: Human Scoundrel  
size: Medium  
type: Humanoid  
subtype: Human  
alignment: Any  
ac: 15  
hp: 55  
hit_dice: 10d8 + 10  
speed: 30 ft.  
stats: [13, 16, 12, 10, 10, 14]  
  
 
skillsaves:  
- <skill-name>:
- Deception: 4
- Sleight of Hand: 5
- Stealth: 5
senses: passive Perception 10  
languages: Common  
cr: 3  

traits:  
- [<trait-name>, <trait-description>]
- [Ambusher, "In the first round of combat, the scoundrel has advantage on attack rolls against any surprised creature."]
- [Exploit Opening (3/Day), "When the raider makes an attack, they have advantage on the attack roll."]
- [Hit Em Where It Hurts, "When the scoundrel has advantage on a weapon attack roll, the attack deals an extra 7 (2d6) damage on a hit."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Rapier, "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8 + 3) piercing damage, and the scoundrel can make a dagger attack against the target with advantage."]
- [Dagger, "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 5 (1d4 + 3) piercing damage."]

- ...    
reactions:  
- [<reaction-name>, <reaction-description>] 

- ...  
```