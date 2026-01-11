```statblock  
name: Mycete
size: Medium  
type: Humanoid 
subtype: Tiefling  
alignment: Lawful Evil  
ac: 14 
hp: 38  
hit_dice: 5d8 + 8  
speed: 30 ft.  
stats: [9, 12, 14, 10, 16, 12]  
 
saves:   
- Int: 2
- Wis: 5
skillsaves: 
- Insight: 5
- Perception: 5
- Nature: 2
- Survival: 5
damage_resistances: fire
damage_immunities: necrotic
senses: darkvision 60 ft.,passive Perception 15  
languages: Common, Infernal  
cr: 2  

traits:  
- [<trait-name>, <trait-description>]
- [Necrotic Absorption, "Whenever Mycete is subjected to necrotic damage, she takes no damage and instead regains a number of hit points equal to the necrotic damage dealt."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Parasitic Spores, "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 30 ft., one target. Hit: 7 (2d6) necrotic damage, and if the target is a creature, Mycete regains 3 (1d6) hit points."]
- [Fungal Growth, "Mycete causes fungi to proliferate from a point she can see within 60 feet of her. Solid surfaces in a 10-foot square centered on that point become difficult terrain, and a creature who enters that area for the first time on a turn or starts their turn there must succeed on a DC 13 Constitution saving throw or be poisoned for 1 minute (save ends at end of turn)."]
- [Animate Husks(1/Day), "Mycete animates three rotting zombies, who appear in unoccupied spaces Mycete can see within 30 feet of her. The zombies act immediately after Mycete on the same initiative count and follow her verbal orders. If Mycete dies, the zombies are destroyed."]
- [Spore Eruption(BA), "Mycete destroys a rotting zombie under her control, and the zombie violently erupts with toxic spores. Each enemy within 5 feet of the zombie must make a DC 13 Constitution saving throw, taking 9 (2d8) necrotic damage on a failed save, or half as much damage on a successful one."]


- ...  
```