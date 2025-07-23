```statblock  
name: Shadow FM  
size: Medium  
type: Undead   
alignment: Chaotiv Evil  
ac: 12  
hp: 13  
hit_dice: 3d8  
speed: 40 ft.  
stats: [6, 14, 11, 10, 10, 14]    

skillsaves:  
- <skill-name>:
- Stealth: 4 
damage_resistances: acid, lightning, necrotic, thunder; bludgeoning, piercing, and slashing from mundane attacks Damage Immunities cold, poison  
damage_immunities:  cold, poison
condition_immunities: dazed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained   
senses: darkvision 60 ft., passive Perception 10  
languages: the languages they knew in life  
cr: 1/2   
traits:  
- [<trait-name>, <trait-description>]
- [Sunlight Weakness, "While in dim light or darkness, the shadow can take the Hide action as a bonus action."]
- [Chilling Phasing, "The shadow can move through other creatures and objects as if they were difficult terrain. The shadow takes 5 (1d10) force damage if they end their turn inside an object. A creature takes 1 cold damage the first time a shadow passes through them on a turn."]
- [Dark Stalker, "While in dim light or darkness, the shadow has advantage on Dexterity (Stealth) checks."]
- ...  
actions:  
- [<trait-name>, <trait-description>] 
- [Chilling Grasp, "Melee Spell Attack: +4 to hit, reach 5 ft., one creature. Hit: 6 (1d8 + 2) cold damage, and the target’s Dexterity score is reduced by 2. The target dies if this reduces its Dexterity to 0. Otherwise, the reduction lasts until the target finishes a short or long rest"]
- [Freezing Dark(1/Day), "The shadow pours magical darkness out of their hand in a 15-foot cone. A creature with darkvision who isn’t an incorporeal Undead can’t see through this darkness, and light can’t illuminate it. Each creature in this darkness when it first appears must succeed on a DC 12 Constitution saving throw or take 7 (2d6) cold damage. The darkness remains in that area for 1 minute or until the shadow is destroyed."]
- [Shadow Bind(BA), "The shadow targets one creature they can see within 15 feet of them who is in bright or dim light. The target must succeed on a DC 12 Strength saving throw or be grappled by their own shadow (escape DC 12). The grapple ends if the target is no longer in bright or dim light, or if the shadow who used this bonus action is destroyed."]
- ...  
