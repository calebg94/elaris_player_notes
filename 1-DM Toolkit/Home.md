---
obsidianUIMode: preview
---


> [!cards|4]
> **Map**
> [![[elaris_final.jpg]]](2-World/Elaris/Elaris.md)
> 
> **Journey Board**
> [![[JourneyBoard.png\|sban htiny ctr]]](Journey%20Board)
>
> **Link**
> [![[AdventureIcon.png\|sban htiny ctr]]](2-World/Elaris/Elaris.md)
> 
> **Party**
> [![[PartyLogo.jpg\|sban htiny ctr p+t]]|](1%20Party%20Party)

`BUTTON[newJournal]` `BUTTON[newPlayer]`

> [!infobox]
> # Session Journals
> ```dataview
TABLE WITHOUT ID link(file.name) AS "Session Date", Status, players
from "1-Session Journals"
where (type = "Session Journal")
SORT file.name DESC

```dataview  
TABLE WITHOUT ID link(file.name) AS "Character Name", Player, Class, Race, level, Role  
from "1-Party"  
where (Role = "Player")  
where (Status = "Active")  
```

# Recently Modified NPCs 

```dataview  
TABLE WITHOUT ID link(file.name) AS "NPC Name", Gender, Race, Age, Location, AssociatedGroup  
FROM "3-Mechanics/NPCs"
WHERE (NoteIcon = "npc") 
SORT file.mtime DESC
LIMIT 10
```

`BUTTON[newNPC]` `BUTTON[newNPCwb]` 
# Recently Modified Locations

```dataview  
TABLE WITHOUT ID link(file.name) AS "Location Name", type, Government, Community-Size, size, population  
FROM "2-World"
WHERE (NoteIcon = "Settlement")  
SORT file.mtime DESC
LIMIT 10
```
`BUTTON[newLocation]`  `BUTTON[newGroup]` `BUTTON[button_quest]`  `BUTTON[newMagicItem]` 

# Recently Modified Notes
```dataview
TABLE WITHOUT ID
    link(file.path, file.folder + " / " + file.name) AS "Note",
    file.mtime AS "Last modified"
FROM "/"
WHERE file.mtime >= date(today) - dur(30 days)
AND file.name != this.file.name
    AND !contains(file.path, "z_Assets")
    AND !contains(file.path, "Inline Scripts")
    AND !contains(file.path, "z_Templates")
    AND !contains(file.path, "daily notes")
    AND !contains(file.path, "BRAT")
SORT file.mtime DESC
LIMIT 10
```

![[Vault Report]]


