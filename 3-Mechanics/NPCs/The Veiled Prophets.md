---
AssociatedGroup: "[[The Crimson Dominion]]"
Gender: Male
Race: 
Age: Unknown
Class:
  - Uknown
Alignment: Lawful Evil
Character-Role: Speakers of the Divine Flame
Location: Varkuun
NoteIcon: npc
Vitality: Unknown
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
> ![[veilied_prophets.png]]
> [[veilied_prophets.png]]
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

The **Veil of Prophets** is not one person, but a group of faceless figures cloaked in crimson robes, their faces **concealed by obsidian masks**. No one outside the Dominion’s inner sanctum knows their identities—some believe they are kept alive by divine fire, others that they are **vessels possessed by an ancient spirit of order**. Each edict is spoken with one voice, delivered through flame-lit holograms or mirrored pools across the empire. Their word is law, and they claim to **speak on behalf of “The Flame That Watches.”** While rigid, their decrees have protected the Dominion from chaos for centuries.  
Opposition within is rare—and brief.

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

