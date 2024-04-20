---
title: Earthquake
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: "Players Handbook.pdf"
page: 236
tags:
  - DnD/Spells/Evocation
  - DnD/Spells/Class/Sorcerer
  - DnD/Spells/Class/Druid
  - DnD/Spells/Class/Cleric


---

##### Back: [[Magic]] || Book: [Players Handbook](https://drive.google.com/drive/folders/1O5bhpYizcIT5xxAoLOuzCRht_PVS7VSG?usp=sharing) || Page: 236

# Earthquake
- ![[earthquake.png]]
- **Casting:**
    - **Casting Time:** 1 action
    - **Duration:** Concentration, up to 1 minute
    - **Range:** 500 feet
    - **Ritual:** No
    - **Concentration:** Yes
- **Classes:**
    - [[Sorcerer]]
    - [[Druid]]
    - [[Cleric]]

- **Info:**
    - **Level:** 8th
    - **School:** Evocation
- **Components:**
    - VSM
    - A pinch of dirt, a piece of rock, and a lump of clay

## Description:
You create a seismic disturbance at a point on the ground that you can see within range. For the duration, an intense tremor rips through the ground in a 100-foot-radius circle centered on that point and shakes creatures and structures in contact with the ground in that area. \n The ground in the area becomes difficult terrain. Each creature on the ground that is concentrating must make a Constitution saving throw. On a failed save, the creature's concentration is broken. \n When you cast this spell and at the end of each turn you spend concentrating on it, each creature on the ground in the area must make a Dexterity saving throw. On a failed save, the creature is knocked prone. \n This spell can have additional effects depending on the terrain in the area, as determined by the GM. \n**Fissures**: Fissures open throughout the spell's area at the start of your next turn after you cast the spell. A total of 1d6 such fissures open in locations chosen by the GM. Each is 1d10 x 10 feet deep, 10 feet wide, and extends from one edge of the spell's area to the opposite side. A creature standing on a spot where a fissure opens must succeed on a Dexterity saving throw or fall in. A creature that successfully saves moves with the fissure's edge as it opens. \n A fissure that opens beneath a structure causes it to automatically collapse (see below). \n**Structures**: The tremor deals 50 bludgeoning damage to any structure in contact with the ground in the area when you cast the spell and at the start of each of your turns until the spell ends. If a structure drops to 0 hit points, it collapses and potentially damages nearby creatures. A creature within half the distance of a structure's height must make a Dexterity saving throw. On a failed save, the creature takes 5d6 bludgeoning damage, is knocked prone, and is buried in the rubble, requiring a DC 20 Strength (Athletics) check as an action to escape. The GM can adjust the DC higher or lower, depending on the nature of the rubble. On a successful save, the creature takes half as much damage and doesn't fall prone or become buried.



---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Earthquake"
> image: [[earthquake.png]]
> level: "8th"
> school: "Evocation"
> class: "Sorcerer,Druid,Cleric"
> duration: "Concentration, up to 1 minute"
> ritual: "No"
> casting_time: "1 action"
> range: "500 feet"
>
> components: VSM
> comp_m: "a pinch of dirt, a piece of rock, and a lump of clay"
>
> description: "You create a seismic disturbance at a point on the ground that you can see within range. For the duration, an intense tremor rips through the ground in a 100-foot-radius circle centered on that point and shakes creatures and structures in contact with the ground in that area. \n The ground in the area becomes difficult terrain. Each creature on the ground that is concentrating must make a Constitution saving throw. On a failed save, the creature's concentration is broken. \n When you cast this spell and at the end of each turn you spend concentrating on it, each creature on the ground in the area must make a Dexterity saving throw. On a failed save, the creature is knocked prone. \n This spell can have additional effects depending on the terrain in the area, as determined by the GM. \n**Fissures**: Fissures open throughout the spell's area at the start of your next turn after you cast the spell. A total of 1d6 such fissures open in locations chosen by the GM. Each is 1d10 x 10 feet deep, 10 feet wide, and extends from one edge of the spell's area to the opposite side. A creature standing on a spot where a fissure opens must succeed on a Dexterity saving throw or fall in. A creature that successfully saves moves with the fissure's edge as it opens. \n A fissure that opens beneath a structure causes it to automatically collapse (see below). \n**Structures**: The tremor deals 50 bludgeoning damage to any structure in contact with the ground in the area when you cast the spell and at the start of each of your turns until the spell ends. If a structure drops to 0 hit points, it collapses and potentially damages nearby creatures. A creature within half the distance of a structure's height must make a Dexterity saving throw. On a failed save, the creature takes 5d6 bludgeoning damage, is knocked prone, and is buried in the rubble, requiring a DC 20 Strength (Athletics) check as an action to escape. The GM can adjust the DC higher or lower, depending on the nature of the rubble. On a successful save, the creature takes half as much damage and doesn't fall prone or become buried."
> higher_level: ""
> ```
