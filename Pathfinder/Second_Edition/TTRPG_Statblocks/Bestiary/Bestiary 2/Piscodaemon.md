---
noteType: pf2eMonster
aliases: "Piscodaemon"
tags: 
  - pf2e/creature/type/fiend
  - pf2e/creature/level/10
statblock: true
statblock-link: "#Piscodaemon"
name: "Piscodaemon"
hp: 200
ac: 28
modifier: 19
level: 10
---
### Piscodaemon
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B2"
name: "Piscodaemon"
level: "Creature 10"
alignment: "NE"
size: "Medium"
trait_03: "Amphibious"
trait_04: "Daemon"
trait_05: "Fiend"
perception:
  - name: "Perception"
    desc: "Perception +19; __darkvision__, __see invisibility__;"
languages: "Common, Daemonic;  telepathy 100 feet;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +22 (1d20+22); __Intimidation__: +19 (1d20+19); __Medicine__: +17 (1d20+17); __Stealth__: +22 (1d20+22); __Survival__: +19 (1d20+19); "
abilityMods: [6, 4, 6, 2, 3, 3]

abilities_mid:
  - name: "Attack of Opportunity"
    desc: "⬲ "
  - name: "Enhance Venom"
    desc: "⬲ ([[divine]], [[misfortune]], [[necromancy]], [[poison]]); __Trigger__ A creature within 30 feet attempts a saving throw against piscovenom __Effect__  The creature takes an additional 1 (2d8) poison damage even if it succeeds at its save."
abilities_bot:
  - name: "Constrict"
    desc: "⬻  1 (2d10+6) bludgeoning, DC 30."
  - name: "Gory Rend"
    desc: "⬺  The piscodaemon makes two claw [[Strike|Strikes]] against the same creature. If both hit, the creature takes 1 (2d10) [[persistent damage|persistent bleed damage]] and is exposed to piscovenom."
  - name: "Piscovenom"
    desc: " ([[poison]]);  __Saving Throw__ DC 30 Fortitude. __Maximum Duration__ 6 rounds __Stage 1__ 1 (1d8) poison and [[enfeebled|enfeebled 1]] (1 round) __Stage 2__ 1 (2d8) poison and [[enfeebled|enfeebled 1]] (1 round) __Stage 3__ 1 (4d8) poison and [[enfeebled|enfeebled 2]] (1 round)"

speed: 25 feet, swim 40 feet

ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__: +22 (1d20+22); __Ref__: +16 (1d20+16); __Will__: +19 (1d20+19);"
health:
  - name: HP
    desc: "200;  __Immunities__ poison, death effects; __Weaknesses__ good 10;"


attacks:
  - name: Melee
    desc: "⬻ claw +23 ([[evil]], [[magical]]); __Damage__ 1 (2d10+12) slashing plus 1 (1d6) evil and Grab"
  - name: Melee
    desc: "⬻ tentacle +23 ([[agile]], [[evil]], [[magical]]); __Damage__ 1 (2d6+12) bludgeoning plus 1 (1d6) evil and piscovenom"

spellcasting:
  - name: "Divine Innate Spells"
    desc: "DC 29; __1st__ [[detect alignment]] at will; good only, [[detect poison]] (at will); __4th__ [[dimension door]] (at will), [[stinking cloud]] (3); __5th__ [[dimension door]]; __Constant__ __(2nd)__ [[see invisibility]];"
sourcebook: "_Bestiary 2_, page 58."
```

### Encounter
```encounter-table
name: Piscodaemon
creatures:
  - 1: Piscodaemon
```