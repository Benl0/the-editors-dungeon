---
cssclass: 
date: 2024-03-05
publish: true
type: Magic
book: "[[Players Handbook.pdf]]"
tags:
  - "#DnD/Spells/Transmutation"
back: "[[Magic]]"
stablock: inline
---
Back: 


```statblock
layout: Spells
source: "SRD"
source: "SRD"
name: "Animate Objects"
image: [[animate-object.png]]
level: "5"
school: "Transmutation"
class: "Bard, Sorcerer, Wizard"
duration: "Concentration, up to 1 minute"
ritual: "No"
casting_time: "1 action"
range: "120 feet"

components:
- name: "V"
- name: "S"
- name: ""
comp_m: ""

description: "Objects come to life at your command. Choose up to ten nonmagical objects within range that are not being worn or carried. Medium targets count as two objects, Large targets count as four objects, Huge targets count as eight objects. You can't animate any object larger than Huge. Each target animates and becomes a creature under your control until the spell ends or until reduced to 0 hit points.\n\nAs a bonus action, you can mentally command any creature you made with this spell if the creature is within 500 feet of you (if you control multiple creatures, you can command any or all of them at the same time, issuing the same command to each one). You decide what action the creature will take and where it will move during its next turn, or you can issue a general command, such as to guard a particular chamber or corridor. If you issue no commands, the creature only defends itself against hostile creatures. Once given an order, the creature continues to follow it until its task is complete.\nAn animated object is a construct with AC, hit points, attacks, Strength, and Dexterity determined by its size. Its Constitution is 10 and its Intelligence and Wisdom are 3, and its Charisma is 1. Its speed is 30 feet; if the object lacks legs or other appendages it can use for locomotion, it instead has a flying speed of 30 feet and can hover. If the object is securely attached to a surface or a larger object, such as a chain bolted to a wall, its speed is 0. It has blindsight with a radius of 30 feet and is blind beyond that distance. When the animated object drops to 0 hit points, it reverts to its original object form, and any remaining damage carries over to its original object form.\n\nIf you command an object to attack, it can make a single melee attack against a creature within 5 feet of it. It makes a slam attack with an attack bonus and bludgeoning damage determined by its size. The DM might rule that a specific object inflicts slashing or piercing damage based on its form."
higher_level: "If you cast this spell using a spell slot of 6th level or higher, you can animate two additional objects for each slot level above 5th."
```

| Size   | HP  | AC | Str | Dex | Attack                            |
|--------|-----|----|-----|-----|-----------------------------------|
| Tiny   | 20  | 18 |  4  |  18 | +8 to hit, 1d4 + 4 damage        |
| Small  | 25  | 16 |  6  |  14 | +6 to hit, 1d8 + 2 damage        |
| Medium | 40  | 13 | 10  |  12 | +5 to hit, 2d6 + 1 damage        |
| Large  | 50  | 10 | 14  |  10 | +6 to hit, 2d10 + 2 damage       |
| Huge   | 80  | 10 | 18  |   6 | +8 to hit, 2d12 + 4 damage       |

