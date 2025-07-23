```statblock  
name: Human Trickshot  
size: Medium  
type: Humanoid  
subtype: Human  
alignment: Any  
ac: 14  
hp: 39  
hit_dice: 6d8+12  
speed: 30 ft.  
stats: [12, 18, 14, 10, 14, 14]  
  
 
skillsaves:  
- <skill-name>:
- Perception: 4
- Stealth: 6 
senses: passive Perception 14  
languages: Common  
cr: 2  

traits:  
- [<trait-name>, <trait-description>]  
- [Exploit Opening (3/Day), "When the raider makes an attack, they have advantage on the attack roll."]
- [Point Blank Shooting, "When the trickshot hits a creature within 30 feet of them with a ranged weapon attack, they deal an extra 7 (2d6) piercing damage. Additionally, being within 5 feet of an enemy doesn’t impose disadvantage on the trickshot’s ranged attack rolls."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Heavy Crossbow, "Ranged Weapon Attack: +6 to hit, range 100/400 ft., one target. Hit: 9 (1d10 + 4) piercing damage."]
- [Bayonet, "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6 + 4) piercing damage."]
- [Ricochet Bolt(Recharge 5 - 6), "he trickshot uses a spe cial ricocheting bolt to make one Heavy Crossbow attack against a target within 100 feet of them, then a second Heavy Crossbow attack against a different target within 30 feet of the first target."]
- ...    
reactions:  
- [<reaction-name>, <reaction-description>] 

```