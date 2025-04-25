---
questObtained: 
questName: Explore the monastery
questStatus: Not Started
questGiver: "[[Arjhan]]"
questLocationObtained: "[[Sol'Vareth 1|Sol'Vareth 1]]"
questSessionObtained: "[[1-Session Journals/2000-01-01.md|2000-01-01]]"
questNotes: 
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

Describe the quest here. 

### Quest Objective

- Fight past the ghost monks to get to the main building of the monastery
- Search the monastery for the mission map fragment and any information on why the island is ruined

### Rewards

- [[Monk Scrolls]]
- [[Map Fragment]]
