```statblock  
name: Human Storm Wizard 
size: Medium  
type: Humanoid  
subtype: Human  
alignment: Any  
ac: 12 (15 with mage armor)  
hp: 75  
hit_dice: 10d8 + 30  
speed: 30 ft.  
stats: [10, 14, 16, 18, 14, 10]  
saves:
 - Int: 7
 - Wis: 5
skillsaves:  
- <skill-name>:
- Arcana: 7
- History: 7
senses: passive Perception 12  
languages: Common  
cr: 6  

traits:  
- [<trait-name>, <trait-description>]  
- [Exploit Opening (3/Day), "When the raider makes an attack, they have advantage on the attack roll."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Arcane Staff, "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 30 ft., one target. Hit: 21 (6d6) lightning damage."]
- [Gust of Wind(1/Day; 2nd-Level Spell; Concentration), "A 10-foot-wide, 60-foot-long line of strong wind gusts from the wizard for 1 minute. Each creature who starts their turn in that area must succeed on a DC 15 Strength saving throw or be pushed 15 feet away from the wizard. Each creature in that area must spend 2 feet of movement for every 1 foot they move toward the wizard. The gust disperses gas or vapor, and it extinguishes candles, torches, and similar unprotected flames. It has a 50 percent chance to extinguish protected flames like lanterns. The wizard can use a bonus action to change the direction in which the wind blasts from them."]
- [Lightning Bolt(3/Day; 3rd-Level Spell), "The wizard fires magical lightning in a 5-foot-wide, 100-foot-long line. Each creature in the line must make a DC 15 Dexterity saving throw, taking 28 (8d6) lightning damage on a failed save, or half as much damage on a successful one. The lightning ignites flammable objects in the area that aren’t being worn or carried."]
- [Utility Spells(SSDC 15), "At will: mage hand , prestidigitation, 1/day each: clairvoyance , mage armor , see invisibility , sending "]
- ...    
reactions:  
- [<reaction-name>, <reaction-description>]
- [Arcane Shield(3/Day), "When the wizard is hit by an attack, they magically gain a +5 bonus to AC against that attack, potentially causing it to miss. If the attacker is within 10 feet of the wizard, the attacker must succeed on a DC 15 Constitution saving throw or take 18 (4d8) thunder damage and be pushed 10 feet away from the wizard."]


- ...  
```