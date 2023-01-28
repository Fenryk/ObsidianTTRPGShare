---
noteType: pf2eMonster
aliases: "Giant Ant"
tags: 
  - pf2e/creature/type/animal
  - pf2e/creature/level/2
statblock: true
statblock-link: "#Giant Ant"
name: "Giant Ant"
hp: 30
ac: 18
modifier: 7
level: 2
---
### Giant Ant
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B2"
name: "Giant Ant"
level: "Creature 2"
alignment: "N"
size: "Medium"
trait_03: "Animal"
perception:
  - name: "Perception"
    desc: "Perception +7; __darkvision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +8 (1d20+8); __Survival__: +7 (1d20+7); "
abilityMods: [4, 1, 4, -5, 1, -4]

abilities_bot:
  - name: "Giant Ant Venom"
    desc: " ([[poison]]);  __Saving Throw__ DC 18 Fortitude. __Maximum Duration__ 4 rounds __Stage 1__ 1 (1d8) poison and [[enfeebled|enfeebled 1]] (1 round) __Stage 2__ 1 (1d10) poison and [[enfeebled|enfeebled 2]] (1 round) __Stage 3__ 1 (1d12) poison and [[enfeebled|enfeebled 3]] (1 round)"
  - name: "Haul Away"
    desc: "⬻ __Requirements__ The giant ant has a Large or smaller creature [[grabbed|grabbed]]  __Effect__  The giant ant [[Stride|Strides]] up to its full Speed, carrying the [[grabbed|grabbed]] creature with it. It is [[encumbered|encumbered]] if the [[grabbed|grabbed]] creature is Medium or larger."

speed: 40 feet, climb 20 feet

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +10 (1d20+10); __Ref__: +7 (1d20+7); __Will__: +5 (1d20+5);"
health:
  - name: HP
    desc: "30; "


attacks:
  - name: Melee
    desc: "⬻ mandibles +11 __Damage__ 1 (1d8+4) slashing plus Grab"
  - name: Melee
    desc: "⬻ stinger +11 ([[agile]]); __Damage__ 1 (1d6+4) piercing plus giant ant venom"

sourcebook: "_Bestiary 2_, page 20."
```

### Encounter
```encounter-table
name: Giant Ant
creatures:
  - 1: Giant Ant
```