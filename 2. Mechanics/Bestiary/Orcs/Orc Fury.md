```statblock  
name: Orc Fury  
size: Medium   
type: Humanoid  
subtype: Orc  
alignment: Any  
ac: 13  
hp: 22  
hit_dice: 3d8 + 9  
speed: 35ft.  
stats: [17, 12, 16, 9, 11, 12]  
  
saves:    
- Str: 5
skillsaves:     
- Athletics: 5 
senses: darkvison 60ft., passive Perception 10  
languages: Common, Orc  
cr: 1/2    
traits:  
- [<trait-name>, <trait-description>]
- [Relentless(1/Turn), "When the fury isn’t incapacitated and they are reduced to 0 hit points but not killed outright, they can make an attack against an enemy (no action required) before the hit point reduction is resolved. If the attack hits and its damage reduces the target to 0 hit points, the fury drops to 1 hit point instead of 0 hit points."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Haymaker Greataxe, "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12 + 3) slashing damage, or 12 (1d12 + 6) slashing damage if the target is prone. If the target is a Medium or smaller creature, they must succeed on a DC 13 Strength saving throw or be knocked prone"]
- [Javelin, "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. Hit: 6 (1d6 + 3) pierc ing damage."]
- [Healing Rally(1/Day)(BA), "The fury regains 5 hit points."]
- ...  

```