---
questObtained: 
questStatus: Not Started
questGiver: "[[Varnok]]"
questLocationObtained: "[[2-World/Elaris/Sol'Vareth/Monk Monastery|Monk Monastery]]"
questSessionObtained: 
questNotes: Path of Memory
questLootAvail: 
questLookEarned: 
NoteIcon: quest
obsidianUIMode: preview
tags:
  - quest
---

<%*
const hasTitle = !tp.file.title.startsWith("NewQuest");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Quest Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>
# `=this.file.name`

> [!infobox]+
> # `=this.file.name`
> ## Quest Details
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
![[lantern_ritual.png]]

### Quest Objective

- List the objectives here.

### Rewards

- List the rewards here.
