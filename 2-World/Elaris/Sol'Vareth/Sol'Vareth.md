---
width: 2048
height: 1642
scale: 25
distance: 268
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: Outpost
Alignment: Chaotic Evil
Government: Autocracy
type: Settlement
politics: Lordship
leader: 
guildsgroups:
  - Thieves Guild 1
  - Cult 1
  - Guiled 1
region:
  - This area
  - Of this area
size: Small city
population: 0
commonraces:
  - Humans
  - Elves
  - Dwarves
religion:
  - Monk
  - Lathander
exports:
  - Something
imports:
  - Something Else
---

<%*
const hasTitle = !tp.file.title.startsWith("NewLocation");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Location Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name` 
> ![[sol_vareth_map_overview.png]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `VIEW[{type}][text]` |
> Size | `VIEW[{size}][text]` |
> Region | `VIEW[{region}][text]` |
> ###### Travel (`VIEW[{Travel Calculator#HoursPerDay}][math]` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]: `VIEW[{Travel Calculator#ExhaustionLevel}][math]`
> Destination |  Travel Days  |
> ---|---|
> [[Voonlar]] | 🕓: `VIEW[round((88* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `VIEW[{politics}][text]` |
> Ruler | `VIEW[{leader}][text]`|
> Defense | `VIEW[{defences}][text]`|
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `VIEW[{population}][text]` |
> Races | `VIEW[{commonraces}][text]`|
> Temples | `VIEW[{religion}][text]` |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `VIEW[{exports}][text]` |
> Imports | `VIEW[{imports}][text]` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> ```dataview
table WITHOUT ID link(file.name) AS "Group", link(Leader) AS "Leader"
where contains( PrimaryHome, this.file.name)


# `=this.file.name`
## Overview
**_Sol’Vareth—an untamed land of ancient whispers and shifting fates._**

_Rugged mountains rise from the northern highlands like stone sentinels, their peaks dusted with mist and mystery. Tucked into those heights, almost hidden among wind-swept pines, rests the ancient_ **Monk Monastery**_, a place of quiet discipline and forgotten wisdom. Gusts rings what bells are left in the monastery, echoing like a memory through the valleys below._

_Descending into the heartland, the wilds give way to lush valleys where old paths twist through forests and meadows. It’s here, nestled beneath the gaze of the mountains, that you find_ **The Hollowed Hearth**_—a weathered tavern built to welcome all to this land of legend. Its hearth always warm, its ale strong, and its stories stronger still. Travelers, drifters, and exiles alike gather here, sharing rumors of beasts in the woods, relics unearthed, and strange lights on the smaller isle to the north._

But beneath the beauty and stillness of Sol’Vareth lies a tension—an island holding its breath. Old magics stir beneath root and stone. Forgotten ruins murmur in dreams. And something moves across the land with purpose, waking things best left sleeping.

## Notable NPCs
* Mayastan Arjhan (owns the Hollowed Hearth)
* Varnok (Protector of Vuremodor)
* Vuremodor (Last remaining dragon, charged with cleansing the stone)

## Profile
Placeholder

## Story
Placeholder

## Points of Interest
* The Hollowed Hearth
* Monk Monastery
* Cave holding Vuremodor

## Valuables
Placeholder

## Internal Relationships
Placeholder

## Outward Relationships
Placeholder

## Background
Placeholder

## Additional Details
Placeholder


```leaflet
### Tutorial: https://youtu.be/54EyMzJP5DU
### id must be unique
id: sol_vareth_icons
image: 
- [[sol_vareth_icons.png|Sol'Vareth Notable Places]]
- [[sol_vareth_icons.png|Sol'Vareth Notable Places]]
height: 900px
width: 80%
### This sets where the map starts by default. Set it to the middle (half) of your bounds. 
lat: 50
long: 50
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map. 
minZoom: 0
### Max zoom is 18. 
maxZoom: 18
### Hover mouse over the Reset Zoom icon to see your current zoom level. 
defaultZoom: 16.5
### How far it zooms in or out with each step. Can be in decimals. 
zoomDelta: 0.5
### This is a string so can be any text. Change it to match your maps measurement scale. 
unit: feet
scale: 1
```

<br>

> [!warning] Levels
> This map contains layers. Use the icon in the top right to switch between layers. 
> This is handy for mapping different levels in buildings/dungeons. 