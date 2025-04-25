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

<%*
const hasTitle = !tp.file.title.startsWith("NewQuest");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Quest Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>
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

You awaken with a **gasp**.  
The air is thick with smoke. Heat prickles your skin like needles.  
The **village is burning**—but it’s not just any village. It's **your village**.  
The sky is an open wound above you. Screams echo. Magic flickers in your hands, but no spell seems to hold.

Then, like a bell toll, you hear **your name**.

**“Tzardface!”**  
But it's not an enemy—  
It’s your familys' **voices**, calling from within the flames.

You **run**. You try to cast spells. You reach for your spellbook.  
But every time, you're **too late**.

- Your **magic fizzles**, or the enemies vanish before you strike.
    
- The faces of your family **fade into smoke** just as you reach them.
    
- The scene **resets** again… and again.
    

And then... silence

From the smoke steps a figure—taller, older, cloaked in soot and pain stricken across his face.  
His robes are tattered, but his eyes are **calm**. Empty, but knowing.

> **“Still chasing shadows?”** he asks.  
> **“Still thinking vengeance will bring them peace? Or you?”**

He raises a hand. The flame stops in midair.  
A single moment hangs suspended.

“Tzarface... what is your reaction? How do you react to these visions?”

### Encounter Options

##### **Attack the vision in fury (vengeance)**

	- TzarFace rejects the echo’s words. The smoke churns. A **soldier materializes**—armor blackened, face sneering, blade drawn. The one who led the razing of his home.
    
	- **“They died begging,”** he growls, **“and still you do nothing.”**
    
	- **The figure draws a staff—an exact mirror of TzarFace’s staff —and strikes.**
      
* **Mechanics:

	- Initiative is rolled. TzarFace fights a **spectral warrior** (AC 16, HP 30, deals 1d10 psychic damage).
    

	- The fight is personal—spells may fizzle on a 1–2 unless fueled by emotion (Charisma check DC 13 per round to bypass).
    

	- Upon killing the figure, the vision collapses—revealing **dozens of bodies** in the ash. All familiar. All silent.
    

* **Outcome:

	- Take 2d8 psychic damage.
    
	- "You’ve won. But look at what remains. What has your fire bought you?"
    

* **Result:

	* Gains inspiration.

	* But takes 2d8 psychic damage and has disadvantage on persuasion/intimidation checks until his next long rest (his rage unbalanced him).

##### Speak to the vision (seeking closure)

* TzarFace steps into the square. The flames part, revealing the figures of his **children and wife**, seated as if in quiet meditation. They do not burn. They simply… wait.

* He kneels. Places a hand on their shoulders. They look at him. Not in fear. Not in judgment.  
    Just… _waiting for him to stop chasing ghosts._

* His wife speaks: **“You’ve carried our ashes long enough. Let us go. Let yourself live again.”**

The fire dims. The wind settles. The loop ends.


* **Mechanics:

	- TzarFace may roll a **DC 15 Insight or Arcana check** to interpret the illusion’s origin (it’s drawn from the Heart’s manipulation of grief).

	- Succeeding grants further understanding of the Heart’s **emotional targeting** magic.
    

* **Outcome:

	- **Healing insight: Advantage on Wisdom and Insight checks, 1/**per long rest

	- Emotionally, TzarFace **feels the weight lift**—not gone, but no longer suffocating.
    

  
##### **Walk away (acceptance)**

- TzarFace stands still. Watches the fire. Then simply… turns.
    

- He **walks**.  
    He doesn’t run. Doesn’t speak. Doesn’t strike.
    
- He leaves the burning village behind. The voices of his children **do not cry out** again.  
    But a whisper follows in the smoke:
    
    - > **“Then live for us, Tzarface. Vengance will only bring misery.”**
        
- The fire doesn’t chase him. The battlefield falls away.  
    Ahead lies **sky**. Cool air. Silence.
    
- **Result:

	- True to thy self: Gain **one use of rerolling a failed save or check related to fear, identity, or grief** before the next long rest.
    
	- His next long rest is **dreamless**—for the first time in years.
    
- DM prompt:
	- > "You didn’t abandon them. You refused to be buried with them. And that’s not weakness—it’s honor. You take their lives with you as you carry on."
    

### Failure State: **Frozen in Time**

If TzarFace **refuses to act**, lashes out at everything, or breaks down in indecision:

The illusion implodes. The village burns brighter.  
His staff cracks. The echo of his voice fades.

> **“If you do not choose a path, the fire will choose for you.”**

He awakens trembling, the taste of ash in his mouth.

* **Result:
	- **Takes 3d6 psychic damage.**
    
	- **Disadvantage on all spellcasting checks** (concentration, attack rolls, etc.) until his next long rest.
