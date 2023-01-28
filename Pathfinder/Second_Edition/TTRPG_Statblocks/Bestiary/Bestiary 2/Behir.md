---
noteType: pf2eMonster
aliases: "Behir"
tags: 
  - pf2e/creature/type/beast
  - pf2e/creature/level/8
statblock: true
statblock-link: "#Behir"
name: "Behir"
hp: 140
ac: 27
modifier: 17
level: 8
---
### Behir
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B2"
name: "Behir"
level: "Creature 8"
alignment: "N"
size: "Huge"
trait_03: "Beast"
trait_04: "Electricity"
perception:
  - name: "Perception"
    desc: "Perception +17; __darkvision__;"
languages: "Draconic; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +16 (1d20+16); __Athletics__: +19 (1d20+19); __Intimidation__: +18 (1d20+18); __Stealth__: +18 (1d20+18); __Survival__: +15 (1d20+15); "
abilityMods: [7, 4, 5, -2, 3, 4]

abilities_bot:
  - name: "Breath Weapon"
    desc: "⬺ ([[electricity]], [[evocation]], [[primal]]);  The behir breathes lightning that deals 1 (9d6) electricity damage in an 60-foot line (DC 27 basic Reflex save). It can't use Breath Weapon again for 1 (1d4) rounds."
  - name: "Claw Storm"
    desc: "⬽  The behir [[Stride|Strides]] up to its Speed, during which it can walk on air as if it were solid ground, ascending or descending at up to a 45-degree angle. It can make up to four claw [[Strike|Strikes]] at any point during this movement, each against a different target within reach, and it deals an extra 1 (1d6) electricity damage with each [[Strike]]. These attacks count toward the behir's multiple attack penalty, but the multiple attack penalty doesn't increase until after the behir makes all of its attacks. If the behir moves half its Speed or less during a Claw Storm, that movement doesn't trigger reactions. The behir can't use Claw Storm if it has a creature wrapped in its coils. At the end of Claw Storm, it drifts downward up to 60 feet to the ground, landing softly and taking no damage from the fall. If it descends further than 60 feet, it takes damage normally from the remaining fall."
  - name: "Constrict"
    desc: "⬻  1 (2d6+7) bludgeoning, DC 27."
  - name: "Swallow Whole"
    desc: "⬻ ([[attack]]);  Large, 1 (2d12+7) bludgeoning, Rupture 21."
  - name: "Wrap in Coils"
    desc: "⬻ __Requirements__ The behir has a creature either [[restrained|restrained]] or [[grabbed|grabbed]] in its jaws  __Effect__  The behir moves the creature into its coils, freeing its jaws. The creature remains [[grabbed|grabbed]] and takes 1 (1d6+6) slashing damage. The behir's coils can hold as many creatures as will fit in its space."

speed: 30 feet, climb 15 feet

ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__: +19 (1d20+19); __Ref__: +16 (1d20+16); __Will__: +15 (1d20+15);"
health:
  - name: HP
    desc: "140; "


attacks:
  - name: Melee
    desc: "⬻ jaws +18 ([[reach|reach 15 feet]]); __Damage__ 1 (2d12+10) piercing plus Grab"
  - name: Melee
    desc: "⬻ claw +18 ([[agile]]); __Damage__ 1 (2d6+10) slashing"

sourcebook: "_Bestiary 2_, page 38."
```

### Encounter
```encounter-table
name: Behir
creatures:
  - 1: Behir
```