---
title: Summon Aberration
publish: true
cssclass:
  - dashboard
date: 2024-04-20 18:30
type: magic
book: "Tashas Cauldron of Everything.pdf"
page: 109
tags:
  - DnD/Spells/Conjuration
  - DnD/Spells/Class/Wizard
  - DnD/Spells/Class/Warlock


---

##### Back: [[Magic]] || Book: [Tashas Cauldron of Everything](https://drive.google.com/drive/folders/1O5bhpYizcIT5xxAoLOuzCRht_PVS7VSG?usp=sharing) || Page: 109

# Summon Aberration

- **Casting:**
    - **Casting Time:** 1 action
    - **Duration:** Concentration, up to 1 hour
    - **Range:** 90 feet
    - **Ritual:** No
    - **Concentration:** Yes
- **Classes:**
    - [[Wizard]]
    - [[Warlock]]

- **Info:**
    - **Level:** 4th
    - **School:** Conjuration
- **Components:**
    - VSM
    - A pickled tentacle and an eyeball in a platinum-inlaid vial worth at least 400 gp

## Description:
You call forth an aberrant spirit. It manifests in an unoccupied space that you can see within range. This corporeal form uses the Aberrant Spirit stat block. When you cast the spell, choose Beholderkin, Slaad, or Star Spawn. The creature resembles an aberration Of that kind, which determines certain traits in its stat block. The creature disappears when it drops to 0 hit points or when the spell ends.

The creature is an ally to you and your companions. In combat, the creature shares your initiative count, but it takes its turn immediately after yours. It obeys your verbal commands (no action required by you). If you don't issue any, it takes the Dodge action and uses its move to avoid danger.

## At Higher Levels:
When you cast this spell using a spell slot of 5th level or higher, use the higher level wherever the spell's level appears in the stat block.

---

> [!BUG]- GM's Corner
>
> ```statblock
> layout: Spells
> source: "Tashas Cauldron of Everything"
> name: "Summon Aberration"
> image: 
> level: "4th"
> school: "Conjuration"
> class: "Wizard,Warlock"
> duration: "Concentration, up to 1 hour"
> ritual: "No"
> casting_time: "1 action"
> range: "90 feet"
>
> components: VSM
> comp_m: "a pickled tentacle and an eyeball in a platinum-inlaid vial worth at least 400 gp"
>
> description: "You call forth an aberrant spirit. It manifests in an unoccupied space that you can see within range. This corporeal form uses the Aberrant Spirit stat block. When you cast the spell, choose Beholderkin, Slaad, or Star Spawn. The creature resembles an aberration Of that kind, which determines certain traits in its stat block. The creature disappears when it drops to 0 hit points or when the spell ends.\n\nThe creature is an ally to you and your companions. In combat, the creature shares your initiative count, but it takes its turn immediately after yours. It obeys your verbal commands (no action required by you). If you don't issue any, it takes the Dodge action and uses its move to avoid danger."
> higher_level: "When you cast this spell using a spell slot of 5th level or higher, use the higher level wherever the spell's level appears in the stat block."
> ```
> ---
>
> ```statblock
> source: "Tashas Cauldron of Everything"
> name: "Aberrant Spirit"
> size: "Medium"
> type: "aberration"
> ac: "11 + the level of the spell (natural armor)"
> hp: "40 + 10 for each spell level above 4th"
> speed: 30ft.; fly 30ft. (hover) (beholderkin only)
> stats: [16, 10, 15, 16, 10, 6]
> cr: "equals your bonus"
> damage_immunities: "psychic"
> senses: "Darkvision 60ft., passive Perception 10"
> languages: "Deep Speech, understands the languages you speak"
> traits:
>   - name: "Regeneration (Slaad Only)."
>     desc: "The aberration regains 5 hit points at the start of its turn if it has at least 1 hit point"
>   - name: "Whispering Aura (Star Spawn Only)."
>     desc: "At the start of each of the aberration's turns, each creature within 5 feet of the aberration must succeed on a Wisdom saving throw against your spell save DC or take 2d6 psychic damage. provided that the aberration isn't incapacitated."
> actions:
>   - name: "Multiattack."
>     desc: "The aberration makes a number of attacks equal to half this spell's level (rounded down)."
>   - name: "Claws (Slaad Only)."
>     desc: "Melee Weapon Attack: your spell attack modifier to hit, reach 5 ft., one target.\nHit: 1d10 + 3 + the spell's level slashing damage. If the target is a creature, it can't regain hit points until the start of the aberration's next turn."
>   - name: "Eye Ray (Beholderkin Only)."
>     desc: "Ranged Spell Attack: your spell attack modifier to hit, range 150 ft., one creature.\nHit: 1d8 + 3 + the spell's level psychic damage."
>   - name: "Psychic Slam (Star Spawn Only)."
>     desc: "Melee Spell Attack: your spell attack modifier to hit, reach 5 ft., one creature.\nHit: 1d8 + 3 + the spell's level psychic damage."
>   ```


