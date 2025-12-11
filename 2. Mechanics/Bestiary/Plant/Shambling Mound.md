```statblock  
name: Shambling Mound  
size: Gargantuan  
type: Plant  
subtype: string  
alignment: Unaligned  
ac: 13  
hp: 155  
hit_dice: 10d20 + 50  
speed: 20 ft.,  
stats: [20, 7, 20, 5, 10, 8]    
saves:    
skillsaves:  
- Con: 8      
damage_immunities: poison  
condition_immunities: blinded, charmed, deafened, flanked, frightened, poisoned, prone  
senses: blindsight 120 ft. (blind beyond this radius), passive Perception 10 
languages: /  
cr: 5    
traits:  
- [<trait-name>, <trait-description>]
- [Engulfing Sack, "The mound has a vegetative sack on their body where they carry engulfed creatures. The sack can be attacked (AC 15; 50 hit points; immunity to poison and psychic damage), which deals no damage to the mound. Destroying the sack frees creatures trapped by the mound’s Engulf action. The mound regrows the sack at the beginning of their next turn."]
- [False Appearance, "While the mound remains motionless, they are indistinguishable from an ordinary mass of vegetation."]  
- ...  
actions:  
- [<trait-name>, <trait-description>] 
- [Multiattack, "The mound makes two Vine Lash attacks. They can replace one attack with a use of Engulf, if available."]
- [Vine Lash, "Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 60 ft., one target. Hit: 14 (2d8 + 5) piercing damage. If the target is Medium or smaller, the mound can pull the target up to 30 feet toward them."]
- [Engulf(5-6), "The mound reaches out with writhing vines and attempts to pull in up to two Medium or smaller creatures within 30 feet of them. Each target must succeed on a DC 16 Strength saving throw or be engulfed in the mound’s engulfing sack. An engulfed creature is restrained, has total cover against attacks and other effects outside the mound, and takes 7 (2d6) poison damage at the start of each of the mound’s turns. When the mound moves, the engulfed creature moves with them. If the mound dies or their engulfing sack is destroyed, each engulfed creature is freed and shunted to an unoccupied space of their choice within 5 feet of the mound"] 
- ...    
reactions:  
- [<reaction-name>, <reaction-description>]
- [Poison Froth, "When the mound takes damage, the inside of their engulfing sack churns with poison. Each creature engulfed by the mound takes 3 (1d6) poison damage, and the mound regains a number of hit points equal to the total damage dealt by this reaction to creatures in their sack"]  
- ...  
```