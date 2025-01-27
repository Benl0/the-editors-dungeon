---
title: Teleport
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: "Players Handbook.pdf"
page: 281
tags:
  - DnD/Spells/Conjuration
  - DnD/Spells/Lv7
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Sorcerer
  - DnD/Spells/Class/Bard

---

##### Back: [[Magic]] || Book: [Players Handbook](https://drive.google.com/drive/folders/1O5bhpYizcIT5xxAoLOuzCRht_PVS7VSG?usp=sharing) || Page: 281

# Teleport
- ![[blink.png]]
- **Casting:**
    - **Casting Time:** 1 action
    - **Duration:** Instantaneous
    - **Range:** 10 feet
    - **Ritual:** No
    - **Concentration:** No
- **Classes:**
    - [[Wizard]]
    - [[Sorcerer]]
    - [[Bard]]

- **Info:**
    - **Level:** 7th
    - **School:** Conjuration
- **Components:**
    - V


## Description:
This spell instantly transports you and up to eight willing creatures of your choice that you can see within range, or a single object that you can see within range, to a destination you select. If you target an object, it must be able to fit entirely inside a 10-foot cube, and it can't be held or carried by an unwilling creature. 

 The destination you choose must be known to you, and it must be on the same plane of existence as you. Your familiarity with the destination determines whether you arrive there successfully. The GM rolls d100 and consults the table. 

| Familiarity       | Mishap | Similar Area | Off Target | On Target |
| ----------------- | :----: | :----------: | :--------: | :-------: |
| Permanent circle  |   -    |      -       |     -      |  01-100   |
| Associated object |   -    |      -       |     -      |  01-100   |
| Very familiar     | 01-05  |    06-13     |   14-24    |  25-100   |
| Seen casually     | 01-33  |    34-43     |   44-53    |  54-100   |
| Viewed once       | 01-43  |    44-53     |   54-73    |  74-100   |
| Description       | 01-43  |    44-53     |   54-73    |  74-100   |
| False destination | 01-50  |    51-100    |     -      |     -     |

### Familiarity
1. "**Permanent circle**" means a permanent teleportation circle whose sigil sequence you know.
2. "**Associated object**" means that you possess an object taken from the desired destination within the last six months, such as a book from a wizard's library, bed linen from a royal suite, or a chunk of marble from a lich's secret tomb.
3. "**Very familiar**" is a place you have been very often, a place you have carefully studied, or a place you can see when you cast the spell.
4. "**Seen casually**" is someplace you have seen more than once but with which you aren't very familiar.
5. "**Viewed once**" is a place you have seen once, possibly using magic.
6. "**Description**" is a place whose location and appearance you know through someone else's description, perhaps from a map.
7. "**False destination**" is a place that doesn't exist. Perhaps you tried to scry an enemy's sanctum but instead viewed an illusion, or you are attempting to teleport to a familiar location that no longer exists.

### On Target
You and your group (or the target object) appear where you want to.
### Off Target
You and your group (or the target object) appear a random distance away from the destination in a random direction. Distance off target is 1d10 x 1d10 percent of the distance that was to be traveled. For example, if you tried to travel 120 miles, landed off target, and rolled a 5 and 3 on the two d10s, then you would be off target by 15 percent, or 18 miles. The GM determines the direction off target randomly by rolling a d8 and designating 1 as north, 2 as northeast, 3 as east, and so on around the points of the compass. If you were teleporting to a coastal city and wound up 18 miles out at sea, you could be in trouble.
### Similar Area
You and your group (or the target object) wind up in a different area that's visually or thematically similar to the target area. If you are heading for your home laboratory, for example, you might wind up in another wizard's laboratory or in an alchemical supply shop that has many of the same tools and implements as your laboratory. Generally, you appear in the closest similar place, but since the spell has no range limit, you could conceivably wind up anywhere on the plane.
### Mishap
The spell's unpredictable magic results in a difficult journey. Each teleporting creature (or the target object) takes 3d10 force damage, and the GM rerolls on the table to see where you wind up (multiple mishaps can occur, dealing damage each time).



---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Players Handbook"
> name: "Teleport"
> image: [[blink.png]]
> level: "7th"
> school: "Conjuration"
> class: "Wizard,Sorcerer,Bard"
> duration: "Instantaneous"
> ritual: "No"
> casting_time: "1 action"
> range: "10 feet"
>
> components: V
> comp_m: ""
>
> description: "This spell instantly transports you and up to eight willing creatures of your choice that you can see within range, or a single object that you can see within range, to a destination you select. If you target an object, it must be able to fit entirely inside a 10-foot cube, and it can't be held or carried by an unwilling creature. \n\n The destination you choose must be known to you, and it must be on the same plane of existence as you. Your familiarity with the destination determines whether you arrive there successfully. The GM rolls d100 and consults the table. **Familiarity:** 'Permanent circle' means a permanent teleportation circle whose sigil sequence you know.\n\n 'Associated object' means that you possess an object taken from the desired destination within the last six months, such as a book from a wizard's library, bed linen from a royal suite, or a chunk of marble from a lich's secret tomb. \n\n 'Very familiar' is a place you have been very often, a place you have carefully studied, or a place you can see when you cast the spell.\n\n'Seen casually' is someplace you have seen more than once but with which you aren't very familiar.\n\n'Viewed once' is a place you have seen once, possibly using magic.\n\n'Description' is a place whose location and appearance you know through someone else's description, perhaps from a map.\n\n'False destination' is a place that doesn't exist. Perhaps you tried to scry an enemy's sanctum but instead viewed an illusion, or you are attempting to teleport to a familiar location that no longer exists. \n\n**On Target:** You and your group (or the target object) appear where you want to. \n\n**Off Target:** You and your group (or the target object) appear a random distance away from the destination in a random direction. Distance off target is 1d10 x 1d10 percent of the distance that was to be traveled. For example, if you tried to travel 120 miles, landed off target, and rolled a 5 and 3 on the two d10s, then you would be off target by 15 percent, or 18 miles. The GM determines the direction off target randomly by rolling a d8 and designating 1 as north, 2 as northeast, 3 as east, and so on around the points of the compass. If you were teleporting to a coastal city and wound up 18 miles out at sea, you could be in trouble. \n\n**Similar Area:** You and your group (or the target object) wind up in a different area that's visually or thematically similar to the target area. If you are heading for your home laboratory, for example, you might wind up in another wizard's laboratory or in an alchemical supply shop that has many of the same tools and implements as your laboratory. Generally, you appear in the closest similar place, but since the spell has no range limit, you could conceivably wind up anywhere on the plane. \n\n**Mishap:** The spell's unpredictable magic results in a difficult journey. Each teleporting creature (or the target object) takes 3d10 force damage, and the GM rerolls on the table to see where you wind up (multiple mishaps can occur, dealing damage each time)."
> higher_level: ""
> ```
