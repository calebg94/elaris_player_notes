---
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: City
Alignment: Lawful Evil
Government: Theocratic Totalitarianism
type: Settlement
politics: Lordship
leader: "[[The Veiled Prophets]]"
guildsgroups:
  - "[[The Crimson Dominion]]"
region:
  - "[[Elaris]]"
size: Medium City
population: 
commonraces:
  - Humans
religion: The Ever-Burning
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
> ![[varkuun.png]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `VIEW[{type}][text]` |
> Size | `VIEW[{size}][text]` |
> Region | `VIEW[{region}][text]` |
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


## Overview
Varkuun is the blackstone heart of the Crimson Dominion—a towering city-fortress built into the spine of Durnhaldir. Perched between craggy stone cliffs and wind-swept valleys, Varkuun is not merely a capital—it is a **cathedral of obedience**, a city forged in fire and fear. Massive obsidian walls ring the city in concentric tiers, each ward dedicated to a different tenet of the Flame's Doctrine. Crimson banners hang from obsidian towers, and the streets are lit by magical braziers that never go out, casting the city in a perpetual, holy glow.

No laughter echoes here. Only prayer, decree, and the hiss of molten forges.

## Notable NPCs
- **Inquisitor Varn Helros** — High-ranking inquisitor tasked with rooting out heresy and interpreting flame-borne prophecies. Feared even among the Dominion elite. Known for his obsidian armor inlaid with red gemstone eyes.
    
- **Mother-Seer Aelira** — Blind prophetess who walks the sacred halls of the Flame Spire. Said to speak directly for the Veil. She delivers omens through ritual burns and ash-readings.
    
- **Acolyte Vex Tarn** — A young initiate with doubts in his heart and forbidden questions in his journal. Possible contact for PCs investigating the cracks in the Dominion.
    
- **Pyremason Kadran Vohl** — Overseer of the Emberforges. Holds knowledge of ancient flame-bound relics and the construction of fire-souled automatons.

## Points of Interest
- **The Flame Spire:** A towering obsidian ziggurat at the city’s core. Houses the Veil of Prophets and burns with a divine flame that never dims.
    
- **The Trial Chambers:** Public arenas for judgment and execution by fire, where divine will is interpreted through combustion.
    
- **The Emberforges:** The industrial soul of the city. Artifacts, weapons, and war constructs are born here in flame and shadow.
    
- **Ashen Garden:** A bleak sanctuary of gray trees and black flowers where citizens meditate on sacrifice and duty.
    
- **The Cleansing Vaults:** Sealed chambers rumored to contain failed prophets, cursed relics, or creatures touched by divine wrath.

## Valuables
- **Ashglass Crystals:** Rare black-red crystals found only beneath the Emberwrought Reaches, used to power divine constructs.
    
- **Contracts of Flame:** Soul-binding scrolls stored in the Flame Spire, signed in ash-blood by rulers who swore eternal obedience.
    
- **The Ember Codex:** A forbidden tome said to predate the Dominion—describes the true origin of the Flame and implies it may be a **sentient entity**.
    
- **The Mask of Mercy:** A relic hidden deep within the Cleansing Vaults. Said to have belonged to the last Dominion inquisitor who chose to forgive rather than burn.

## Internal Relationships

- Rigid hierarchy creates political tension between inquisitors, prophets, and military commanders.
    
- Secret cells of doubters and heretics exist beneath the surface—most notably, those who speak of the "Old Flame" or seek forbidden compassion.

## Outward Relationships

- **Hostile** toward the Veylas Tribes, whom they consider anarchic and dangerous.
    
- **Tense diplomacy** with the Luminous Compact; they view the Compact's arcane focus as arrogant, though beneficial in trade.
    
- **Openly hunting** members of the Final Harmony, who they see as blasphemers twisting the Flame for personal power.

## Background
Varkuun was founded atop the bones of a heretic kingdom after the Flame Wars. It was the first city consecrated by the **Veil of Prophets**, who channeled divine fire to cleanse the land and fuse stone with ash. From its inception, Varkuun was never meant to be lived in—it was meant to be **endured**, a test of faith and discipline. Generations have passed under the flame’s gaze, and now its people revere suffering as proof of loyalty.

The city is said to have **vaults beneath its lowest tier** that contain the ashes of fallen gods and the contracts that bound them.

## Additional Details
> **Twist:** Unbeknownst to all but the highest members of the Veil, **Malachai himself is secretly working with the Crimson Dominion**, having struck a covert alliance with the prophets. In public, Dominion inquisitors purge the Final Harmony wherever they’re found—but in secret, the Veil has granted Malachai access to the **divine flame's source**, believing they can control or redirect his ambitions.
> 
> In truth, **Malachai is using the Veil**, leveraging the sentient flame’s power to **stabilize and weaponize the Heart of Dread**. He sees the Veil as a temporary instrument—tools of faith to be discarded once their purpose is served.


