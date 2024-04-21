---
title: Tiny Servant
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: "Xanathars Guide to Everything.pdf"
page: 168
tags:
  - DnD/Spells/Transmutation
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Artificer


---

##### Back: [[Magic]] || Book: [Xanathars Guide to Everything](https://drive.google.com/drive/folders/1O5bhpYizcIT5xxAoLOuzCRht_PVS7VSG?usp=sharing) || Page: 168

# Tiny Servant

- **Casting:**
    - **Casting Time:** 1 minute
    - **Duration:** 8 hours
    - **Range:** Touch
    - **Ritual:** No
    - **Concentration:** No
- **Classes:**
    - [[Wizard]]
    - [[Artificer]]

- **Info:**
    - **Level:** 3rd
    - **School:** Transmutation
- **Components:**
    - VS


## Description:
You touch one Tiny, nonmagical object that isn't attached to another object or a surface and isn't being carried by another creature. The target animates and sprouts little arms and legs, becoming a creature under your control until the spell ends or the creature drops to 0 hit points. See the stat block for its statistics.

As a bonus action, you can mentally command the creature if it is within 120 feet of you. (If you control multiple creatures with this spell, you can command any or all of them at the same time, issuing the same command to each one.) You decide what action the creature will take and where it will move during its next turn, or you can issue a simple, general command, such as to fetch a key, stand watch, or stack some books. If you issue no commands, the servant does nothing other than defend itself against hostile creatures. Once given an order, the servant continues to follow that order until its task is complete.

When the creature drops to 0 hit points, it reverts to its original form, and any remaining damage carries over to that form.

## At Higher Levels:
When you cast this spell using a spell slot of 4th level or higher, you can animate two additional objects for each slot level above 3rd.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Xanathars Guide to Everything"
> name: "Tiny Servant"
> image: 
> level: "3rd"
> school: "Transmutation"
> class: "Wizard,Artificer"
> duration: "8 hours"
> ritual: "No"
> casting_time: "1 minute"
> range: "Touch"
>
> components: VS
> comp_m: ""
>
> description: "You touch one Tiny, nonmagical object that isn't attached to another object or a surface and isn't being carried by another creature. The target animates and sprouts little arms and legs, becoming a creature under your control until the spell ends or the creature drops to 0 hit points. See the stat block for its statistics.\n\nAs a bonus action, you can mentally command the creature if it is within 120 feet of you. (If you control multiple creatures with this spell, you can command any or all of them at the same time, issuing the same command to each one.) You decide what action the creature will take and where it will move during its next turn, or you can issue a simple, general command, such as to fetch a key, stand watch, or stack some books. If you issue no commands, the servant does nothing other than defend itself against hostile creatures. Once given an order, the servant continues to follow that order until its task is complete.\n\nWhen the creature drops to 0 hit points, it reverts to its original form, and any remaining damage carries over to that form."
> higher_level: "When you cast this spell using a spell slot of 4th level or higher, you can animate two additional objects for each slot level above 3rd."
> ```
> 
> ---
>
> ```statblock
> image: [[tiny-servant.png]]
> source: "Xanathars Guide to Everything"
> name: Tiny Servant
> size: Tiny
> type: construct
> alignment: unaligned
> ac: 15 (natural armor)
> hp: 10 4d4
> speed: 30ft.; climb 30ft.
> stats:
>   - 4
>   - 16
>   - 10
>   - 2
>   - 10
>   - 1
> cr: 
> senses: "Blindsight 60ft. (blind beyond this radius), passive Perception 10"
> languages: 
> damage_immunities: "Poison, Psychic"
> condition_immunities: "blinded, charmed, deafened, exhaustion, frightened, paralyzed, petrified, poisoned"
> 
> actions:
>   - name: "Slam."
>     desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target.\nHit 5 (1d4 + 3) bludgeoning damage."
> ```

