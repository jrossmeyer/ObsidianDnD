```statblock  
name: Stirge  
size: Tiny  
type: string  
subtype: string  
alignment: Unaligned  
ac: 13  
hp: 4  
hit_dice: 1d4 + 2  
speed: 10 ft., fly 30 ft.  
stats: [4, 17, 14, 3, 10, 2]    
saves:    
- <skill-name>: number
- Stealth: 5    
senses: darkvision 60 ft., passive Perception 10  
languages: /  
cr: 0.25   
traits:  
- [<trait-name>, <trait-description>]
- [Tiny Target, "If the stirge is reduced to 0 hit points by any damage other than psychic while attached to another creature, that creature takes damage equal to half that dealt to the stirge"]  
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Proboscis, "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 3 piercing damage, and the stirge can attach to the target and enter their space. While attached, the stirge moves with the target and can’t make Proboscis attacks. A creature who can reach the stirge can use an action to detach the stirge, shunting them into the nearest unoccupied space of the stirge’s choice. The stirge also detaches if they become grappled, incapacitated, prone, or restrained."]
- [Drain Essence, "The stirge sips the life essence of a creature they are attached to who isn’t a Construct or an Undead. T he creature loses 3 hit points and must succeed on a DC 12 Constitution saving throw or be poisoned until the end of the stirge’s next turn. If the creature is already poisoned, they also become dazed until the end of the stirge’s next turn."]  
- ...  

```