---
AssociatedGroup: "[[The Veylas Tribes]]"
Gender: Female
Race:
  - Firbolg
Age: "34"
Class:
  - Druid
Alignment: Neutral Good
Character-Role: Druidic Leader
Location: Vandrel's Reach
NoteIcon: npc
Vitality: Healthy
exampleProperty: z_Assets/Decks/Business Card Dungeon/Dungeon16.png
---
<%*
const hasTitle = !tp.file.title.startsWith("NewNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
> ![[ashani.png]]
> [[ashani.png]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `VIEW[{Location}][text]`  |
> Group | `VIEW[{AssociatedGroup}][text]` |
> Sex | `VIEW[{Gender}][text]` |
> Race | `VIEW[{Race}][text]` |
> Age | `VIEW[{Age}][text]`|
> Condition | `VIEW[{Vitality}][text]` |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `VIEW[{Alignment}][text]` |
> Class | `VIEW[{Class}][text]`  |
> Character Role | `VIEW[{Character-Role}][text]` |

# `=this.file.name`
## Profile

Ashani speaks not with authority, but with the **trust of the land itself**. Born under an eclipse and raised by three tribal traditions, she has long been a symbol of **unity and balance** among the Veylas. Her communion with the Verdant Heart—a living intelligence said to dwell beneath the forest—grants her visions that are both prophecy and memory. She **rarely speaks in absolutes**, often letting nature or dreams answer for her. Outsiders mistake her gentleness for indecision, but those who threaten the balance soon **learn how wrathful the land can be when guided by her voice.**

> [!info] Statblock
> ```statblock
> name: Individual
> monster: Commoner
> columns: 1
> ```

```encounter-table
name: Individual
creatures:
 - 1: Commoner
```

