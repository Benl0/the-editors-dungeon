---
title: Wall of Ice
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: "Players Handbook.pdf"
page: 285
tags:
  - DnD/Spells/Evocation
  - DnD/Spells/Class/Wizard


---

##### Back: [[Magic]] || Book: [Players Handbook](https://drive.google.com/drive/folders/1O5bhpYizcIT5xxAoLOuzCRht_PVS7VSG?usp=sharing) || Page: 285

# Wall of Ice
- ![[wall-of-ice.png]]
- **Casting:**
    - **Casting Time:** 1 action
    - **Duration:** Concentration, up to 10 minutes
    - **Range:** 120 feet
    - **Ritual:** No
    - **Concentration:** Yes
- **Classes:**
    - [[Wizard]]

- **Info:**
    - **Level:** 6th
    - **School:** Evocation
- **Components:**
    - VSM
    - A small piece of quartz

## Description:
You create a wall of ice on a solid surface within range. You can form it into a hemispherical dome or a sphere with a radius of up to 10 feet, or you can shape a flat surface made up of ten 10-foot-square panels. Each panel must be contiguous with another panel. In any form, the wall is 1 foot thick and lasts for the duration.

If the wall cuts through a creature's space when it appears, the creature within its area is pushed to one side of the wall and must make a Dexterity saving throw. On a failed save, the creature takes 10d6 cold damage, or half as much damage on a successful save.

The wall is an object that can be damaged and thus breached. It has AC 12 and 30 hit points per 10-foot section, and it is vulnerable to fire damage. Reducing a 10-foot section of wall to 0 hit points destroys it and leaves behind a sheet of frigid air in the space the wall occupied. A creature moving through the sheet of frigid air for the first time on a turn must make a Constitution saving throw. That creature takes 5d6 cold damage on a failed save, or half as much damage on a successful one.

## At Higher Levels:
When you cast this spells using a spells slot of 7th level or higher, the damage the wall deals when it appears increases by 2d6, and the damage from passing through the sheet of frigid air increases by 1d6, for each slot level above 6th.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Wall of Ice"
> image: [[wall-of-ice.png]]
> level: "6th"
> school: "Evocation"
> class: "Wizard"
> duration: "Concentration, up to 10 minutes"
> ritual: "No"
> casting_time: "1 action"
> range: "120 feet"
>
> components: VSM
> comp_m: "a small piece of quartz"
>
> description: "You create a wall of ice on a solid surface within range. You can form it into a hemispherical dome or a sphere with a radius of up to 10 feet, or you can shape a flat surface made up of ten 10-foot-square panels. Each panel must be contiguous with another panel. In any form, the wall is 1 foot thick and lasts for the duration.\n\nIf the wall cuts through a creature's space when it appears, the creature within its area is pushed to one side of the wall and must make a Dexterity saving throw. On a failed save, the creature takes 10d6 cold damage, or half as much damage on a successful save.\n\nThe wall is an object that can be damaged and thus breached. It has AC 12 and 30 hit points per 10-foot section, and it is vulnerable to fire damage. Reducing a 10-foot section of wall to 0 hit points destroys it and leaves behind a sheet of frigid air in the space the wall occupied. A creature moving through the sheet of frigid air for the first time on a turn must make a Constitution saving throw. That creature takes 5d6 cold damage on a failed save, or half as much damage on a successful one."
> higher_level: "When you cast this spells using a spells slot of 7th level or higher, the damage the wall deals when it appears increases by 2d6, and the damage from passing through the sheet of frigid air increases by 1d6, for each slot level above 6th."
> ```
