```statblock  
name: Uthrak  
size: Medium  
type: Humanoid  
subtype: Human  
alignment: Lawful Evil  
ac: 16  
hp: 144  
hit_dice: 17d8 + 68  
speed: 30 ft.  
stats: [19, 12, 19, 14, 14, 16]    
saves:   
- Str: 7
- Con: 7
skillsaves:  
- <skill-name>: number  
- Athletics: 10
- Deception: 6
- Insight: 5
- Intimidation: 9
- Perception: 5 
senses: passive Perception 15  
languages: Common  
cr: 7   
traits:  
- [<trait-name>, <trait-description>]
- [Bloodstones(3 Uses), "When Baron Uthrak fails a saving throw while holding his magic longsword Nine Lives, he can choose to succeed instead. If he does so, he takes 7 (2d6) necrotic damage as one of the bloodstones set in the sword’s pommel fills with his blood."]
- [Exploit Opening (3/Day), "When Uthrak makes an attack, he has advantage on the attack roll."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Multiattack, "Baron Uthrak makes two attacks using Nine Lives, Whip, or both."]
- [Nine Lives, "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 9 (1d8 + 5) slashing damage plus 3 (1d6) necrotic damage."]
- [Whip, "Melee Weapon Attack: +7 to hit, reach 15 ft., one target. Hit: 6 (1d4 + 4) slashing damage, and the target must succeed on a DC 15 Strength saving throw or be pulled up to 15 feet toward Baron Uthrak."]
- ["Kneel, Peasant!(BA)", "Baron Uthrak kicks a Large or smaller creature within 5 feet of him. The target must succeed on a DC 15 Strength saving throw or take 6 (1d4 + 4) bludgeoning damage and be knocked prone."]
 
- ...  
legendary_actions:  
- [Villain Actions, "Uthrak has three villain actions. He can take each action once during an encounter after an enemy’s turn. He can take these actions in any order but can use only one per round"]
- ["Action 1: Shoot", "Each ally within 60 feet of Uthrak who can hear him can make a ranged weapon attack (no action required)."]
- ["Action 2: Form Up!", "Uthrak and each ally within 60 feet of him who can hear him can move up to their speed without provoking opportunity attacks. Baron Uthrak and each ally enters a defensive stance that lasts until that creature moves or is restrained or incapacitated. When two or more allies in a defensive stance are within 5 feet of each other, attack rolls against them are made with disadvantage."]
- ["Action 3: Lead from the Front", "Uthrak moves up to twice his speed without provoking opportunity attacks. During or after this movement, he can make up to four Nine Lives or Whip attacks with advantage, each against a different target. After he attacks a target in this way, each ally within 5 feet of that target can make a melee attack with advantage against the same target (no action required)."]
- ...  
reactions:  
- [<reaction-name>, <reaction-description>]  
- [Riposte, "When a creature Baron Uthrak can see misses him with a melee attack, Uthrak makes a melee attack against that creature."]
- ...  
```