---
tags:
  - Category/Group
Community-Size: Outpost
Alignment: Lawful Evil
Government: Theocratic Totalitarianism
Leader: "[[The Veiled Prophets]]"
PrimaryHome:
  - Varkuun
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
> ![[crimson_dominion.png]]
> ###### Key Members
> ```dataview
table Race, Gender
where contains( AssociatedGroup, this.file.name)

# `=this.file.name`
## Overview
An empire of blood-bound loyalty, where religion and state are inseparable, and prophecy shapes law.

## Etymology
"Crimson" symbolizes both the blood of loyalty and divine fire. "Dominion" reflects total, unyielding control.
## Activities
- Enforcement of divine law via inquisitions
- Public executions and divine spectacle
- Harvesting magical ore from the mountains of Durnhaldir
- Suppression of forbidden arcana

## Society
### Beliefs
Authoritarian, with rigid class structures. Citizens are assigned roles based on aptitude and prophetic alignment. Believe the world must be purified through divine will. Chaos is the enemy of truth.
### Culture
Spartan aesthetics. Loyalty is art. Most homes have devotional alcoves. Fire motifs appear in banners, armor, and tattoos.

### Religion
Worships a faceless divine flame known as "The Everburning." Faith is state-mandated.

## Possessions
- Obsidian temples and fireforged weapons
- Relics said to contain divine edicts
- Firebound contracts with neighboring empires

## History
Rose from a scorched war between cults and kingdoms. The Veil of Prophets united survivors under a divine mandate of flame and discipline.

## Rumors & Legends
- Their prophets are puppets animated by an ancient elemental.
- One of the Veil's members is immortal and has watched since the founding.
- Their flames do not burn everything—only what the gods reject.


