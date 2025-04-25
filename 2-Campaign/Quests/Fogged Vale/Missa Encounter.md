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
The fog thickens until Missa’s footsteps fall silent. The others vanish. She stands alone at the edge of a battlefield long past—its ash still warm, its banners still waving. Ahead lies a **stone throne**, half built from polished marble, half from bones and iron. It is torn between two styles, as if forged by different hands. Two figures round the throne:

- On the **left**: her **mother**, regal and ethereal, cloaked in moonlight, her hair in woven gold strands. She does not smile, but there is pride in her gaze.  
    **“You carry grace in your blood, child. Lead with logic. Uplift our name.”**
    

- On the **right**: her **father**, bloodied and strong, his war axe dripping crimson that sizzles where it hits the ground. He snarls—but in encouragement.  
    **“You are storm and steel, girl. Take what you’re owed. Burn those who shamed you.”**
    

Between them, the **throne pulses** like a heartbeat.

Each extends a hand.

> **“Choose,”** they say in unison. **“The world will not wait for the indecisive.”**

### Encounter Options
### _Step 1: Reaction & Pressure_

- Ask the player what Missa **feels** first. Does she recoil? Rage? Freeze?
    
- Require a **DC 13 Wisdom saving throw** to avoid being overwhelmed by the duality.
    
    - **Success**: She may choose freely.
        
    - **Failure**: One figure steps closer, whispering louder—**disadvantage** on future Insight/Charisma checks during the trial if she chooses that parent’s path.
        

### Step 2: Memory Check

- Prompt a memory from childhood—one parent teaching her something pivotal.
    
- Ask for a **DC 15 Insight or History check** (player’s choice).
    
    - Success reveals that both parents, though different, **wanted her to live free**.
        
    - Failure feeds the illusion that only **one path can define her**.
        

  
  

### _Option 1:_ **Take the Elven Banner** _(Order & Diplomacy)_

Missa reaches for the moonlit banner. As her fingers grasp the silk, her armor reshapes into silver ceremonial garb. Her calloused hands feel foreign. She is placed upon the throne—nobles bow in silence.

But her mother is gone. The throne is cold. In a mirror beside the dais, her face reflects calm... but her eyes are distant. She is respected. But is she known?

- **Effect:**
    
    - **Order above all: Advantage on Persuasion and Insight checks** per long rest.
        
    - **-2 to melee damage while raging**, as emotional detachment dulls her fury.
        
- **Prompt:**  
    Ask Missa: “How does it feel to be _admired_, but not _understood_?”
    

### _Option 2:_ **Take the Barbarian Banner** _(Fury & Vengeance)_

She grips the bloodied banner. The wind howls. Her muscles surge with tension. Her father steps forward, placing a wolf’s tooth circlet upon her brow.  
The throne becomes a pyre. Her enemies fall beneath her fists.

But her mother fades into mist.  
When she speaks, only **war drums** answer. Her allies stand behind her… not beside her.

- **Effect:**
    
    - **Barbaric honor: +1 to melee weapon damage**, **Advantage on Intimidation checks** 1/per long rest.
        
    - **Disadvantage on Wisdom saves vs charm or deception**, as rage blurs her clarity.
        
- **Prompt:**  
    Ask Missa: “Do you feel powerful—or isolated?”

### _Option 3:_ **Walk into the Mist** _(Carve Her Own Path)_

Missa looks at both. Breathes. Drops her weapon. She turns from the throne—not in defiance, but in clarity. The banners dissolve. Her parents do not stop her.

She walks into the mist. A narrow path forms. Wildflowers bloom between the cracks of stone. Broken swords rise like memorials.

A whisper follows her:

> **“You are not what they made. You are what you become.”**

- **Effect:**
    
    - Gain **Familial** **Inspiration**, and one use of **reroll on any failed check/save related to identity, manipulation, or fear**. You now have two charges of inspiration
        
    - That night, she dreams of her parents—not as judges, but **as proud spirits watching her path unfold.**
        
- **Prompt:**  
    Ask Missa: “If you write your own story, what does the first page say?”
    

_Failure State:_ **Hesitation or Breakdown**

> The throne warps. Her parents argue in unison, louder and louder until the world cracks. The banners catch fire. Her weapon shatters. She is buried beneath judgment and shame.

- **Result**_: Takes_ **3d6 psychic damage**_, and her next rage only lasts 1 round as her anger is overwhelmed by confusion and emotional instability._