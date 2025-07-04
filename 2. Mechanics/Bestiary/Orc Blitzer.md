```statblock  
name: Orc Blitzer  
size: Medium  
type: Humanoid  
subtype: Orc  
alignment: Any Alignment  
ac: 13  
hp: 7   
speed: 35 ft.  
stats: [15, 12, 12, 10, 11, 11]      
senses: darkvision 60ft., passive Perception 10  
languages: Common, Orc  
cr: 1/2    
traits:  
- [<trait-name>, <trait-description>] 
- [Gnashing Horde, "If an enemy the blitzer can see starts their turn within 5 feet of three or more blitzers, the enemy takes 1 piercing damage for each blitzer within 5 feet of them."]
- [Minion, "If the forcecaller takes damage from an attack or as the result of a failed saving throw, their hit points are reduced to 0. If the forcecaller takes damage from another effect, they die if the damage equals or exceeds their hit point maximum; otherwise they take no damage."]
- [Relentless Minion, "When the forcecaller is reduced to 0 hit points while they aren’t incapacitated, they can deal 1 force damage to an enemy within 5 feet of them."]
- ...  
actions:  
- [<trait-name>, <trait-description>] 
- [Spear(Group Attack), "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 1 piercing damage"]
- ...  
 
- ...  
```