---
questObtained: 
questName: Light the Altar of Vowfire
questStatus: Not Started
questGiver: "[[Varnok]]"
questLocationObtained: "[[Sol'Vareth 1|Sol'Vareth 1]]"
questSessionObtained: "[[1-Session Journals/2000-01-01.md|2000-01-01]]"
questNotes: Path of Flame
questLootAvail: 
questLookEarned: 
NoteIcon: quest
obsidianUIMode: preview
tags:
  - quest
---

> [!infobox]+
> # `INPUT[text:questName]`
> ###### Quest Details
> Type |  Stat |
> ---|---|
> Date Obtained | `INPUT[datePicker:questObtained]` |
> Status | `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |
> 

### Map
![[altar_of_vowfire.png]]

### Quest Objective

- Phase 1: **The Scale’s Judgment**

 _As the players enter the ritual circle, the_ **golden scale floats into the air**_, glowing like an ember. Suddenly the scale shoots forward plunging itself into the scale shaped slot in the dragon statue. Varnok steps out from behind the statue:_

> “You must choose 3 among you who must pass judgement before the keepers scale... share your conviction, and prove your worth”
- **Roleplay Challenge:**_Each player must speak_ **a personal vow aloud**_—it can be tied to vengeance, redemption, protection, loyalty, or growth._

**Mechanics:**
- Each vow = a **DC 13 Charisma (Persuasion)** or **Wisdom (Insight)** check.
	- **Pass Outcome:**

		- The scale flares. The past accepts their growth.
		    
		- They may proceed to Phase 2.
    

	- **Fail Outcome:**

		- A flame lashes out from the altar, forcing a **DC 12 Dex save** or take 2d6 fire damage.
		
		- They must **restate their vow** or receive help from an ally before continuing.
- > Phase 2: **Lighting the Vowfire**

> The basin of the altar begins to glow, pulsing like a heart. But it remains unlit.

**Actions Players Can Take (pick one per PC):**

- **Cast or create a fire-based effect** (e.g., _Produce Flame_, _Control Flames_, _Burning Hands_)
    
- **Place a personal item** into the basin—something tied to a past oath or identity
    
- **Inscribe a vow** in Draconic or Common into the scorched stone using tools or a blade
    

- The **Vowfire ignites**—a bright, golden flame bursts into the sky.
    
- The basin absorbs the players’ vows, and their **names are burned faintly into the stone**.
- Search the monastery for the mission map fragment and any information on why the island is ruined
**Phase 3: Echo of the Flame**

Once the Vowfire is successfully lit, the altar glows with radiant light, and the wind carries voices—the echoes of dragonkin initiates long gone.

**Varnok speaks**

> “You who speak the flame… You remember. You mend.”__“And he... still listens.”_

From the flame, a second golden scale of Vuremodor appears—this one etched with a spiral symbol (the mark of balance). It floats in front of the players, encircling them in a warm glow, giving the players a feeling of protection.

### Rewards

- **Vowfire Resurgance:**
	- Grant allies resistance to necrotic or fire damage for 5 minutes (1/day)
