---
PromptInfo:
 promptId: GenEncounter
 name: 🍻 Generate Encounter 🛏️
 description: Generate a enocunter. 
 author: JoshP
 tags: fantasy, ttrpg
 version: 0.0.1
---

## Narrative
_You emerge into a clearing at the heart of the forest. Once, this was a place of harmony—smooth stone rings embedded in the earth, trees growing in concentric circles, the scent of herbs and clean air._

But now, roots are gnarled and choked in black fungus. The leaves above block out the sun completely. Mushrooms weep tar. The very earth seems to breathe in shallow pain. The air this and oppressing.

At the center is a raised circle of stones surrounding a **moss-covered altar**, cracked and bleeding with sap-black ichor.

#### Pre-Ritual
Any PC with druidic or nature-themed background can **attempt to commune** with the forest (DC 13 Wis [Nature] check). If they succeed, they gain a haunting echo of how the grove once sang—a dissonant, but beautiful melody that aids the ritual later.

As you step closer… the forest **screams and the ground shakes**.

**Tactics:**
- The dryads attempt to delay or distract.
- The wolf targets spellcasters.

```encounter
name: Example
creatures:
 - 1: [[Blightbound Dryad]]
 - 2: [[Corrupted Vine Horror]]
 - 2: [[Hollowfang Wolf]]
```

#### Ritual
**Nyx speaks the Oath of Harmony aloud**

###### The Oath of Harmony

> “I speak not as master, but as memory—  
Of grove and glade, of wild song and still stone.  
I have called the forest to rise,  
To strike, to defend, to rage.  
But now, I call it to breathe.
Let the soil remember gentleness.  
Let the roots forget the lash of fire.  
Let the wind carry healing where harm once lingered.
By the blood in my bark,  
By the breath in my vow,  
By the balance I once broke—  
I ask the wild to forgive me.
Grow again. Sing again.  
And I will walk with you, not ahead of you,  
Until your silence is full of life once more.”

###### Ignite the altar with nature magic

- Cast [[produce-flame-xphb|Produce Flame]], [[flame-blade-xphb|Flame Blade]], [[sacred-flame-xphb|Sacred Flame]], or [[druidcraft-xphb|Druidcraft]] to begin burning away the corruption.
    

Nyx makes two checks (DC 13 each):

- Nature, Religion, or Arcana to control the energy
    

**Failure Consequences:**

- The altar resists; dark vines lash out, each player takes 2d6 necrotic damage (DC 12 Dex save for half)
    
- Corruption flares, summoning two more vine blight (CR 1/2)
    

**Success Outcome:**

> The ichor begins to sizzle and recede. Light returns to the canopy in beams. The once-blackened altar glows softly, and grass begins to push up through the cracked ground.

- A **radiant green-and-gold aura** emanates from the altar engulfing Nyx in the warming light
    
- Nyx gains a **permanent mark of the Grove**:
    
    - **Advantage on Nature checks** and range cast [[lesser-restoration-xphb|Lesser Restoration]] **1/day casting of**
    - You feel the forest begin to breathe again, engulfing you in a sense of gratitude and understanding. Harmony and balance have been restored to this altar. 


#### Post-ritual
- **Seed of Renewal:** A tiny seed sprouts in a character’s palm. If planted during a long rest, it will grow into a small blooming flower or miniature tree by morning—marking a personal growth moment.
    
- **Fungus Remnants Puzzle (Optional):** A PC may notice strange fungi that resist the cleansing glow. If investigated, they find a _spore puzzle_ (Arcana/Nature check) hinting that these were _implanted_—possibly connecting to an outside corrupting source (perhaps foreshadowing the Heart of Dread).
- A deep roar is felt through the earth as liquid gold drips where the black ichor used to be. Dripping down to the base of the altar filling scale shaped etching. Once filled the scale glows bright with the an image of the next altar sight in its mirrored face. A faint image of Varnok stands among the trees, not speaking, but watching. Etched on the back of the scale is an inscription _“Speak your truth in flame,  And be judged by its light.”_