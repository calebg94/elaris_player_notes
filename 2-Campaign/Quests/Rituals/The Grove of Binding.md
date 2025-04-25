---
questObtained: 
questName: Cleanse the Grove
questStatus: Not Started
questGiver: "[[Varnok]]"
questLocationObtained: "[[Sol'Vareth 1|Sol'Vareth 1]]"
questSessionObtained: "[[1-Session Journals/2000-01-01.md|2000-01-01]]"
questNotes: Path of Balance
questLootAvail: "[[3-Mechanics/Items/Monk Scrolls.md|Monk Scrolls]]"
questLookEarned: 
NoteIcon: quest
obsidianUIMode: preview
tags:
  - quest
---

> [!infobox]+
> # `INPUT[text:questName]`
> ###### Quest Details
> Type |  Stat |
> ---|---|
> Date Obtained | `INPUT[datePicker:questObtained]` |
> Status | `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |




### Map
![[The Grove of Binding.jpg]]

### Quest Objective

- Defeat the monsters that arrive in the grove to get the ritual site
- **Nyx speaks the Oath of Harmony aloud**

##### The Oath of Harmony

> _“We vow to walk beside the flame, not before it, not behind it.  
> We vow to mend, not sever—to listen, not command.  
> Where root and breath meet, let peace grow.  
> Where rot festers, let light burn it clean.  
> By leaf, by scale, by soul—we remember the balance.”_

- **Nyx speaks the Oath of Harmony aloud**
- **Ignite the altar with nature magic**
	- Cast _Produce Flame_, _Flame Blade_, _Sacred Flame_, or _Druidcraft_ to begin burning away the corruption.
- **Failure Consequences:**

	- The altar resists; dark vines lash out, each player takes 2d6 necrotic damage (DC 12 Dex save for half)
    
	- Corruption flares, summoning two more vine blight (CR 1/2)
- **Success Outcome:**
	- The ichor begins to sizzle and recede. Light returns to the canopy in beams. The once-blackened altar glows softly, and grass begins to push up through the cracked ground.
	- - A radiant green-and-gold aura emanates from the altar engulfing Nyx in the wamring light

### Rewards
- Nyx gains a **permanent mark of the Grove**:
    
    - **Advantage on Nature checks**
        
    - OR a **1/day casting of** [[lesser-restoration-xphb|Lesser Restoration]]
