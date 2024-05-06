---
title: Tsunami
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: "Players Handbook.pdf"
page: 284
tags:
  - DnD/Spells/Conjuration
  - DnD/Spells/Lv8
  - DnD/Spells/Class/Druid

---

##### Back: [[Magic]] || Book: [Players Handbook](https://drive.google.com/drive/folders/1O5bhpYizcIT5xxAoLOuzCRht_PVS7VSG?usp=sharing) || Page: 284

# Tsunami
- ![[tsunami.png]]
- **Casting:**
    - **Casting Time:** 1 minute
    - **Duration:** Concentration, up to 6 rounds
    - **Range:** Sight
    - **Ritual:** No
    - **Concentration:** Yes
- **Classes:**
    - [[Druid]]

- **Info:**
    - **Level:** 8th
    - **School:** Conjuration
- **Components:**
    - VS


## Description:
A wall of water springs into existence at a point you choose within range. You can make the wall up to 300 feet long, 300 feet high, and 50 feet thick. The wall lasts for the duration.

When the wall appears, each creature within its area must make a Strength saving throw. On a failed save, a creature takes 6d10 bludgeoning damage, or half as much damage on a successful save.

At the start of each of your turns after the wall appears, the wall, along with any creatures in it, moves 50 feet away from you. Any Huge or smaller creature inside the wall or whose space the wall enters when it moves must succeed on a Strength saving throw or take 5d10 bludgeoning damage. A creature can take theis damage only once per round. At the end of the turn, the wall's height is reduced by 50 feet, and the damage creatures take from the the spell on subsequent rounds is reduced by 1d10. When the wall reaches 0 feet in height, the spell ends.

A creature caught in the wall can move by swimming. Because of the force of the wave, though, the creature must make a successful Strength (Athletics) check against your spell save DC in order to move at all. If it fails the check, it can't move. A creature that moves out of the area falls to the ground.



---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Tsunami"
> image: [[tsunami.png]]
> level: "8th"
> school: "Conjuration"
> class: "Druid"
> duration: "Concentration, up to 6 rounds"
> ritual: "No"
> casting_time: "1 minute"
> range: "Sight"
>
> components: VS
> comp_m: ""
>
> description: "A wall of water springs into existence at a point you choose within range. You can make the wall up to 300 feet long, 300 feet high, and 50 feet thick. The wall lasts for the duration.\n\nWhen the wall appears, each creature within its area must make a Strength saving throw. On a failed save, a creature takes 6d10 bludgeoning damage, or half as much damage on a successful save.\n\nAt the start of each of your turns after the wall appears, the wall, along with any creatures in it, moves 50 feet away from you. Any Huge or smaller creature inside the wall or whose space the wall enters when it moves must succeed on a Strength saving throw or take 5d10 bludgeoning damage. A creature can take theis damage only once per round. At the end of the turn, the wall's height is reduced by 50 feet, and the damage creatures take from the the spell on subsequent rounds is reduced by 1d10. When the wall reaches 0 feet in height, the spell ends.\n\nA creature caught in the wall can move by swimming. Because of the force of the wave, though, the creature must make a successful Strength (Athletics) check against your spell save DC in order to move at all. If it fails the check, it can't move. A creature that moves out of the area falls to the ground."
> higher_level: ""
> ```