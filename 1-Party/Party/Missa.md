---
NoteIcon: player
aliases:
  - Missa
tags:
  - player
Player: Missa Misunderstood
Role: Player
Class:
  - Barbarian
Race:
  - Half-elf
level: 3
hp: 32
ac: 13
modifier: 3
pasperc: 13
Status: Active
PlayerKnownLanguages:
  - Celestial
  - Common
  - Draconic
  - Elvish
  - Sylvan
faction_standing:
  Harpers: 1
  Magicians: 2
---



[[Pasted image 20220612052639.png]]

# `=this.file.name`

| Image                                              | Char Name         | Player Name    | Class         | Race         | Level         |
| -------------------------------------------------- | ----------------- | -------------- | ------------- | ------------ | ------------- |
| ![[ImagePlaceholder.png\|cover hsmall]] | `=this.file.name` |  `VIEW[{Player}]` | `VIEW[{Class}]` | `VIEW[{Race}]` | `VIEW[{level}]` |

```dataviewjs
const player = dv.current();
const factions = dv.pages('"3-Mechanics/Guilds and Groups"');

let tableData = [];

for (let faction of factions) {
    let factionName = faction.faction;
    let playerStanding = player.faction_standing?.[factionName] || 0;

    // Ensure benefits is treated as an array
    let benefitsList = Array.isArray(faction.benefits) ? faction.benefits : [];

    // Filter benefits the player qualifies for
    let qualifiedBenefits = benefitsList
        .filter(b => playerStanding >= b.standing)
        .map(b => b.reward)
        .join(", "); 

    let primaryContact = faction.primary_contact || "No contact set";

    tableData.push([factionName, playerStanding, qualifiedBenefits || "No benefits yet", primaryContact]);
}

dv.table(["Faction", "Your Standing", "Benefits", "Primary Contact"], tableData);
```

```custom-frames
frame: ConfigureInCustomFramesPlugin
```

