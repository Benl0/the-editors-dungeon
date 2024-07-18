
---

> [!BUG]- GM's Corner
> ```dataview
> TABLE WITHOUT ID
> file.link AS "Character", race AS "Race", class AS "Class", location AS "Home", description AS "Description"
> FROM "300 CAMPAIGNS/Garde"
> WHERE contains(type,"npc") AND faction = this.file.name
> SORT file.name
> ```

