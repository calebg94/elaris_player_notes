---
tags:
  - Category/Group
Community-Size: Outpost
Alignment: Neutral Good
Government: Autocracy
Leader: "[[Ashani Windroot]]"
PrimaryHome:
  - Vandrels Reach
NoteIcon: group
faction: 
primary_contact: 
benefits:
  - standing: 1
    reward: What do they get at level 1?
  - standing: 2
    reward: What do they get at level 2?
  - standing: 3
    reward: What do they get at level 3?
---


<%*  
const hasTitle = !tp.file.title.startsWith("NewGroup");  
let title;  
if (!hasTitle) {  
title = await tp.system.prompt("Group Name");  
await tp.file.rename(title);  
} else {  
title = tp.file.title;  
}  
_%>

> [!infobox]
> # `=this.file.name`
> ![[veylas_tribes.png]]
> ###### Key Members
> ```dataview
table Race, Gender
where contains( AssociatedGroup, this.file.name)

# `=this.file.name`
## Overview
...

## Etymology
"Veylas" comes from an ancient druidic term meaning "those who walk beside the wind."
## Activities
- Stewardship of sacred groves and elemental nexuses
- Seasonal migrations and spirit-guided festivals
- Ritual combat to settle disputes
- Protection of beast-kind and ancient ruins

## Society
### Beliefs
Clan-based, semi-nomadic, and guided by omens. Leadership is fluid and determined by merit, vision, or spiritual bond. Believe in harmony between body, soul, land, and sky. Civilization must bend to nature, not the reverse.
### Culture
Oral histories, bone and wood carving, spirit tattoos. Clothing reflects the elements of one's birth.

### Religion
Animistic. They venerate the Verdant Heart, elemental spirits, and seasonal deities.

## Possessions
- Soulbound totems passed through generations
- Runes carved from living stone
- Elementally awakened beasts

## History
The Veylas are the oldest culture in Elaris, said to have learned from the dragons and stars before any kingdom rose.

## Rumors & Legends
- Some tribes can transform into elemental forms. 
- Their dreams are watched by something older than the gods.
- Sol'Vareth was once part of the Veylas domain, protected by a dragon pact.


