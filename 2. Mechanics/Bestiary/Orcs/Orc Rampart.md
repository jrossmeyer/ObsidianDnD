```statblock  
name: Orc Rampart  
size: Medium   
type: Humanoid  
subtype: Orc  
alignment: Any  
ac: 18  
hp: 42  
hit_dice: 5d8 + 20  
speed: 35ft.  
stats: [18, 12, 18, 10, 11, 12]  
skillsaves:
- Athletics: 6
- Perception: 2
senses: darkvison 60ft., passive Perception 12  
languages: Common, Orc  
cr: 2    
traits:  
- [<trait-name>, <trait-description>]
- [Relentless(1/Turn), "When the rampart isn’t incapacitated and they are reduced to 0 hit points but not killed outright, they can make an attack against an enemy (no action required) before the hit point reduction is resolved. If the attack hits and its damage reduces the target to 0 hit points, the fury drops to 1 hit point instead of 0 hit points."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Multiattack, "The rampart makes two Spear attacks. If the rampart targets the same creature with both attacks, the target has disadvantage on attack rolls against creatures other than the rampart until the start of the rampart’s next turn."]
- [Spear, "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing damage if used with two hands to make a melee attack."]
- ...
reactions:
- [No!, "When an enemy within 5 feet of the rampart targets another creature with an attack, the attacker must target the rampart instead."]

```