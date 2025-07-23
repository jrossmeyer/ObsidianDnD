```statblock  
name: Human Brawler  
size: Medium  
type: Humanoid  
subtype: Human  
alignment: Any  
ac: 14  
hp: 52  
hit_dice: 7d8 + 21  
speed: 30 ft.  
stats: [17, 14, 16, 10, 10, 12]  
  
 
skillsaves:  
- <skill-name>:
- Athletics: 5
- Intimidation: 3
senses: passive Perception 10  
languages: Common  
cr: 2  

traits:  
- [<trait-name>, <trait-description>]  
- [Exploit Opening (3/Day), "When the brawler makes an attack, they have advantage on the attack roll."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Multiattack, "The brawler makes two attacks using Grab, Haymaker, or both."]
- [Grab, "Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller creature. Hit: 5 (1d4 + 3) bludgeoning damage, and the target is grappled (escape DC 13). Until this grapple ends, the brawler can’t grab another creature."]
- [Haymaker, "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4 + 3) bludgeoning damage, or 10 (3d4 + 3) bludgeoning damage against a grappled target."]
- [Throw, "The brawler throws one Medium or smaller creature they are grappling or object they are holding up to 30 feet horizontally. If the thrown target is a creature, they fall prone after this throw. If the thrown target would enter the space of a creature or solid object that is no more than one size smaller than it, the thrown target collides with it and stops in the nearest unoccupied space, taking 3 (1d6) bludgeoning damage for every 10 feet it was thrown. A Large or smaller creature hit by this thrown target must succeed on a DC 13 Dexterity saving throw or take the same amount of damage and fall prone."]
- ...    
reactions:  
- [<reaction-name>, <reaction-description>] 
- [Meath Shield(BA), "When the brawler is grappling a target and is hit by a ranged attack made by another creature the brawler can see, the brawler gains a +2 bonus to AC against the triggering attack. If this bonus causes the attack to miss the brawler, it hits the grappled target instead"]
```