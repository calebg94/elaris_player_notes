---
AssociatedGroup: "[[The Luminous Compact]]"
Gender: Female
Race:
  - Eladrin Elf
Age: "450"
Class:
  - Wizard (Chronurgy)
Alignment: Lawful Neutral
Character-Role: Group Leader
Location: Thalara
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
> ![[velvine_aurase.png]]
> [[velvine_aurase.png]]
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

Velvine Aurasae is the Compact’s eldest sitting councilmember, though her appearance remains ageless thanks to chronomantic rituals. A former inventor and guildmistress of the Arcane Banking Registry, she rose to power not by combat, but by **building systems of debt and loyalty no one dared dismantle**. She believes **progress is inevitable**, and that morality is a luxury for those who don’t shape nations. While often cloaked in diplomacy and gold-threaded robes, she’s known for **silencing opposition via sudden regulatory collapse** or mysterious accidents. Her name is **spoken with both reverence and fear** among aspiring mages.

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

