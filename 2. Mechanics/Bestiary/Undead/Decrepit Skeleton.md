```statblock  
name: Decrepit Skeleton  
size: Medium  
type: Undead  
subtype: string  
alignment: Neutral Evil  
ac: 11  
hp: 6  
speed: 30 ft.  
stats: [11, 13, 10, 7, 10, 4]    
damage_immunities: poison   
senses: darkvision 60 ft., passive Perception 10  
languages: understands the languages they knew in life but can’t speak  
cr: 1   
traits:  
- [<trait-name>, <trait-description>]
- [Bone Weapon, "The skeleton’s weapon attacks are magical. They use their bones as ammunition for their bone bow, regrowing used bones every dusk."]
- [Minion, "If the skeleton takes damage from an attack or as the result of a failed saving throw, their hit points are reduced to 0. If the skeleton takes damage from another effect, they die if the damage equals or exceeds their hit point maximum; otherwise they take no damage."]
- ...  
actions:  
- [<trait-name>, <trait-description>] 
- [Bone Bow(Group Attack), "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit: 1 piercing damage. If the target is a creature and three or more skeleton minions joined the attack, the skeletons can choose another creature they can see within 5 feet of the original target. The second target takes 2 piercing damage."]
- [Bone Knife(Group Attack), "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 1 slashing damage."]
- ...  

```