```statblock  
name: Marsh Hydra  
size: Large  
type: Monstrosity  
subtype: string  
alignment: Unaligned  
ac: 16  
hp: 126  
hit_dice: 12d10 +60  
speed: 30 ft.  
stats: [20, 10, 20, 3, 12, 3]      
skillsaves:  
- <skill-name>: number
- Athletics: 8
- Perception: 7      
condition_immunities: flanked, poisoned, prone  
senses: darkvision 60 ft., passive Perception 17  
languages: -  
cr: 7    
traits:  
- [<trait-name>, <trait-description>]  
- [Multiple Heads, "The marsh hydra has advantage on saving throws against being blinded, charmed, dazed, deafened, frightened, stunned, and knocked unconscious."]
- [Roll Over, "If the marsh hydra moves at least 20 feet straight toward a creature and then hits them with an Entangling Serpents attack on the same turn, that target must succeed on a DC 16 Strength saving throw or be knocked prone."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Multiattack, "The marsh hydra makes two Entangling Serpents attacks. They can replace one attack with a Many Bites attack."]
- [Entangling Serpents, "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14 (2d8 + 5) bludgeoning damage, and the target is grappled (escape DC 16)."]
- [Many Bites, "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 9 (1d8 + 5) piercing damage, and the target must make a DC 16 Constitution saving throw. On a failed save, the target takes 18 (4d8) poison damage and is poisoned until the end of the marsh hydra’s next turn. On a successful save, the target takes half as much damage and isn’t poisoned."]
- [Serpent Suprise, "The marsh hydra activates one of the following effects; if the effect targets another creature, the marsh hydra targets one creature they can see within 30 feet of them: 1. Poison Spit. The targeted creature must succeed on a DC 16 Dexterity saving throw or take 9 (2d8) poison damage and be blinded until the end of the marsh hydra’s next turn. 2. Entrancing Gaze. The targeted creature must succeed on a DC 16 Wisdom saving throw or be charmed by the marsh hydra for 1 minute or until the marsh hydra harms the target (save ends at end of turn). 3. Terrifying Rattle. The targeted creature must succeed on a DC 16 Wisdom saving throw or be frightened by the marsh hydra for 1 minute (save ends at end of turn). 4. Reinforcements. The marsh hydra shuffles which heads are on the outside of their body and regains 10 (3d6) hit points."]
  
   
```