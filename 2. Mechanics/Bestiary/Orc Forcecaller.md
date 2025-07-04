```statblock  
name: Orc Forcecaller  
size: Medium  
type: Humanoid  
subtype: Orc  
alignment: Any Alignment  
ac: 12  
hp: 8   
speed: 35 ft.  
stats: [15, 11, 14, 10, 11, 15]      
senses: darkvision 60ft., passive Perception 10  
languages: Common, Orc  
cr: 1/8    
traits:  
- [<trait-name>, <trait-description>] 
- [Minion, "If the forcecaller takes damage from an attack or as the result of a failed saving throw, their hit points are reduced to 0. If the forcecaller takes damage from another effect, they die if the damage equals or exceeds their hit point maximum; otherwise they take no damage."]
- [Relentless Minion, "When the forcecaller is reduced to 0 hit points while they aren’t incapacitated, they can deal 1 force damage to an enemy within 5 feet of them."]
- ...  
actions:  
- [<trait-name>, <trait-description>] 
- [Chainspoken(Group Attack), ". Melee or Ranged Spell Attack: +3 to hit, reach 5 ft. or range 30/60 ft., one target. Hit: 1 force damage. If two or more forcecallers joined the attack, they can deal the same amount of force damage to another creature within 10 feet of the target."]
- ...  
 
- ...  
```