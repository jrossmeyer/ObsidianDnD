```statblock  
name: Human Death Cultist  
size: Medium  
type: Humanoid  
subtype: Human  
alignment: Any  
ac: 16  
hp: 60  
hit_dice: 8d8 + 24  
speed: 30 ft.  
stats: [16, 10, 16, 14, 18, 12]  
saves:
 - Wis: 6
 - Cha: 3
skillsaves:  
- <skill-name>:
- Intimidation: 3
- Religion: 4
senses: passive Perception 14  
languages: Common  
cr: 4  

traits:  
- [<trait-name>, <trait-description>]  
- [Exploit Opening (3/Day), "When the raider makes an attack, they have advantage on the attack roll."]
- ...  
actions:  
- [<trait-name>, <trait-description>]
- [Scythe, "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10 + 3) slashing damage plus 7 (2d6) necrotic damage, and the cultist regains hit points equal to half the necrotic damage dealt."]
- [Death Bolt, "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 14 (4d6) necrotic damage, and the target’s weapon attacks deal half damage until the start of the cultist’s next turn."]
- [Blackfire Blessing(1/Day), "The cultist empowers up to 10 non-minion allies within 30 feet of them. For 1 minute or until the cultist dies, each creature’s weapons burn with black fire and deal an extra 2 (1d4) necrotic damage on a hit."]
- ["Rise, My Minions!(1/Day)(BA)", "The cultist chooses up to three creatures within 30 feet of them who died within the last minute. These creatures return to life with 1 hit point, but they can’t regain hit points, and they die after 1 minute."]
- ...    
reactions:  
- [<reaction-name>, <reaction-description>]
- [Life from Death, "When a creature the cultist can see within 30 feet of them fails a death saving throw or dies, the cultist siphons their faltering life energy. The cultist chooses a creature within 30 feet of the cultist who isn’t uncon scious, and that creature regains 14 (4d6) hit points."]

- ...  
```