---
title: 
publish: false
cssclasses:
  - dashboard
date: 2024-04-21 12:13
type: moc
tags:
  - Garde/GM
world: Garde
campaign: Garde
---
##### Back: [[Garde]]

# General
- ## Planning
	- [[Campaign Ideas]]
	- [[Story Plan v1]]
	- [[Story plan v2]]
	- [[To Research]]
	- [[Compelling Villains]]
- ## Inspiration
	- [[Monster ideas]]
- ## Reference
	- [[Plugins]]

# Characters
`button-cha-npc`

```dataview
TABLE WITHOUT ID
file.link AS "Character", race AS "Race", class AS "Class", faction AS "Faction", location AS "Home"
FROM "300 CAMPAIGNS/Garde"
WHERE contains(type,"npc")
SORT faction
```

## Factions
```dataview
TABLE WITHOUT ID
file.link AS "Faction", location AS "Location"
FROM "300 CAMPAIGNS/Garde"
WHERE contains(type,"faction")
```

---

# Sessions
`button-ses-recap`  `button-ses-plan`

## Plan
```dataview
TABLE WITHOUT ID
file.link AS "Session", sessionNum AS "n", sessionDate AS "Session date"
FROM "300 CAMPAIGNS/Garde/zGM/SESSIONS"
SORT sessionNum
```


## Recap
```dataview
TABLE WITHOUT ID
file.link AS "Session", sessionNum AS "n", sessionDate AS "Session date"
FROM "300 CAMPAIGNS/Garde/SESSIONS"
WHERE type = "session"
SORT sessionNum
```

---


# Vault Info
- 🗄️ **Recent file updates** `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(10).file.link)`
- 📊 **Stats**
    - File Count: `$=dv.pages().length`
    - Rules: `$=dv.pages('"100 RULES"').length`
    - Reference: `$=dv.pages('"200 REFERENCE"').length`
    - Campaigns: `$=dv.pages('"300 CAMPAIGNS"').length`