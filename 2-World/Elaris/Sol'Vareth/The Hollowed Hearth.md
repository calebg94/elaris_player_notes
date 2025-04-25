---
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: Outpost
Alignment: 
Government: Autocracy
type: Settlement
politics: 
leader: 
guildsgroups: 
region:
  - Sol'Vareth, Elaris
size: Tavern
population: 0
commonraces:
  - Humans
  - Elves
  - Dwarves
  - Dragonkin
religion: 
exports: 
imports:
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
> ![[The Hollowed Hearth.jpg]]
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
Placeholder

## Notable NPCs
Placeholder

## Profile
Placeholder

## Story
Placeholder

## Points of Interest
Placeholder

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

