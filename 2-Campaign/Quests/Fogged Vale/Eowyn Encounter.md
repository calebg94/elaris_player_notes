---
questObtained: 
questStatus: Not Started
questGiver: None
questLocationObtained: "[[2-World/Elaris/Sol'Vareth/Sol'Vareth|Sol'Vareth]]"
questSessionObtained: "[[2025-04-19]]"
questNotes: 
questLootAvail: Boon
questLookEarned: 
NoteIcon: quest
obsidianUIMode: preview
tags:
  - quest
---

# `=this.file.name`

> [!infobox]+
> # `=this.file.name`
> ## Quest Details
> Type |  Stat |
> ---|---|
> Date Obtained | `INPUT[datePicker:questObtained]` |
> Status | `INPUT[inlineSelect(option(Not Started), option(In Progress), option(Complete)):questStatus]` |
> Quest Giver | `INPUT[suggester(optionQuery(#npc)):questGiver]` |
> Quest Location | `INPUT[suggester(optionQuery(#Category/Settlement)):questLocationObtained]` |
> Session Obtained | `INPUT[suggester(optionQuery(#journal)):questSessionObtained]` |
> Available Loot | `INPUT[suggester(optionQuery(#item)):questLootAvail]` |
> Acquired Loot | `INPUT[suggester(optionQuery(#item)):questLookEarned]` |

### Quest Narrative
A bell tolls in the distance.  
The docks of **Blackstone** rise from the fog—gray, slick with rain, echoing with memories. You know this place. Every stone. Every alley.  
But the colors are wrong—**washed out**, like an old painting left too long in the salt air.

The air reeks of **blood and wet rope**.  
Footsteps splash through puddles behind her. The sea crashes silently beyond the port—but no ship creaks. No gulls cry.

Ahead, a scene replays:

> **Thrain**, your mentor, wounded and surrounded, fends off blades with his back to a wall.  
> Eowyn watches from behind a crate, helpless and frozen. Her own voice echoes: **“I’m sorry… I wasn’t fast enough.”**

The scene plays again. And again.  
Each time, she is too late.  
Each time, **he turns his head**, eyes searching, **not with rage—but with sorrow**.

Suddenly, **everything freezes**.  
The flickering lantern above no longer sways. The raindrops hang in the air. And then—**Thrain turns toward her**, stepping out of the memory.

He isn’t bloodied now. He’s calm. Confident. That old grin half-formed beneath his beard.

> **“So, Eowyn...”**  
> “Did the treasure buy your forgiveness?”  
> “Or are you still running?”

The question is **not cruel**—but it cuts deep.

How does Eowyn respond?

### Encounter Options
##### **Option 1: Try to Save Him** _(Rewrite the Past)_

The moment restarts again. Eowyn draws her blade. This time—**she moves**, and she dives into it, trying to stop the inevitable.

>What does Eowyn say or read prompt:
“Not again,” she growls. “I won’t let you fall.”

She fights the attackers in the illusion—slashing, slipping, racing against fate.

**Mechanic**:

* DC 16 Dexterity (Acrobatics or Sleight of Hand) check to reach him in time  
OR  
* Use a healing item or spell if available  
OR  
* Roleplay a desperate action that symbolizes her willingness to _change_ history

- **Outcome**:
    
    - She reaches him—but he still dies in her arms.
        
    - He touches her cheek and says:
        

> _“You weren’t meant to save me. You were meant to survive.”_

- **Reward**:
    
    - Gains **inspiration**.
        
    - Honor among thieves: You feel as if Thrain is watching over you, protecting you in some way. Next time she’s at 0 HP, she automatically stabilizes as if Thrain protects her.
        

##### **Option 2: Tell Him the Truth** (Vulnerability)

Eowyn **steps into the memory**—but doesn’t fight it.  
Instead, she **walks to Thrain** as the loop pauses again.

Her voice shakes.  
She may speak of how she froze, how she hated herself, how the coin in her pocket wasn’t enough.  
She may simply say: “I’m sorry.”

> Thrain chuckles softly, placing a ghostly hand on her shoulder. “You still remember me. That’s all the legacy I need, girl.” Thrain fades from the scene, leaving Eowyn kneeling in the alley. 

#### Mechanics:

- No roll required. **The test is honesty**.  
    Let the player speak freely—ask, “What would Eowyn say if she had one final moment with him?”
    

- **Reward**:
    
    - Gains **advantage on Charisma (Deception, Persuasion, or Intimidation)** checks when talking about her past.
        
    - Thrain's Momento: Once per combat, may **invoke Thrain’s memory** (e.g. flipping a ghostly coin) to reroll a missed attack or failed saving throw.
        

##### **Option 3: Say Goodbye** (Letting Go)

_Eowyn watches. She doesn’t fight. Doesn’t cry. Just_ **walks forward**, kneels, and places her hand on the blood-soaked ground beside Thrain’s body._

> “Goodbye, Captain.”

The scene **shatters like glass**.  
Rain stops midfall. A single beam of sunlight cuts through the mist.  
A **ghostly coin** appears in her hand, warm to the touch.

- **Outcome**:
    
    - Gains **resistance to psychic damage** until the next long rest.
        
    - A ghostly coin—one Thrain once flipped—appears in her hand. It gives **+1 to initiative** when held.
        

##### **Failure State: Panic or Denial**

If Eowyn:

- Refuses to act,
    
- Blames the world, or
    
- Tries to **escape the vision**…
    

The alley closes. Rain turns to flood. Phantom sailors rise from the puddles—**guilt wearing old faces**.

> They drag her beneath the street. The water fills her lungs.  
> A sailor whispers: “We gave you everything. Why couldn’t you face it?”

#### Mechanics:

- Take **3d6 psychic damage**.
    
- Suffer **disadvantage on saving throws against fear or paralysis** until the next long rest.

### After the Trial

As Eowyn walks forward, the harbor fades. She returns to the misted path where her companions await.

- If she succeeded in **peace or power**, the **coin glints faintly** in her pocket.
    
- If she failed, **saltwater** clings to her boots, and her fingers twitch as if holding a blade that’s not there.
    

Before she leaves the mist entirely, she hears Thrain’s voice—faint, but clear:

> **“Don’t forget why we sailed, kid. It wasn’t the gold. It was the wind.”**