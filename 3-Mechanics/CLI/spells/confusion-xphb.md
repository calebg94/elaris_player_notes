---
obsidianUIMode: preview
cssclasses: json5e-spell
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/spell/class/bard
- ttrpg-cli/spell/class/druid
- ttrpg-cli/spell/class/sorcerer
- ttrpg-cli/spell/class/wizard
- ttrpg-cli/spell/level/4th-level
- ttrpg-cli/spell/school/enchantment
- ttrpg-cli/spell/subclass/arcane-trickster
- ttrpg-cli/spell/subclass/eldritch-knight
- ttrpg-cli/spell/subclass/great-old-one-patron
- ttrpg-cli/spell/subclass/trickery-domain
classes:
- Bard
- Cleric (Trickery Domain)
- Druid
- Fighter (Eldritch Knight)
- Rogue (Arcane Trickster)
- Sorcerer
- Warlock (Great Old One Patron)
- Wizard
aliases: ["Confusion"]
---
# Confusion
*4th-level, Enchantment*  


- **Casting time:** 1 Action
- **Range:** 90 feet
- **Components:** V, S, M (three nut shells)
- **Duration:** Concentration, up to 1 minute

Each creature in a 10-foot-radius Sphere centered on a point you choose within range must succeed on a Wisdom saving throw, or that target can't take Bonus Actions or Reactions and must roll `1d10` at the start of each of its turns to determine its behavior for that turn, consulting the table below.

`dice: [](confusion-xphb.md#^1-behavior-for-the-turn)`

| dice: 1d10 | Behavior for the Turn |
|------------|-----------------------|
| 1 | The target doesn't take an action, and it uses all its movement to move. Roll `1d4` for the direction: **1**, north; **2**, east; **3**, south; or **4**, west. |
| 2-6 | The target doesn't move or take actions. |
| 7-8 | The target doesn't move, and it takes the [Attack](3-Mechanics/CLI/rules/actions.md#Attack) action to make one melee attack against a random creature within reach. If none are within reach, the target takes no action. |
| 9-10 | The target chooses its behavior. |
^1-behavior-for-the-turn

At the end of each of its turns, an affected target repeats the save, ending the spell on itself on a success.

**Using a Higher-Level Spell Slot.** The Sphere's radius increases by 5 feet for each spell slot level above 4.

**Classes**: [Sorcerer](3-Mechanics/CLI/lists/list-spells-classes-sorcerer.md); [Rogue (Arcane Trickster)](3-Mechanics/CLI/lists/list-spells-classes-rogue-xphb-arcane-trickster-xphb.md "subclass=XPHB;class=XPHB"); [Fighter (Eldritch Knight)](3-Mechanics/CLI/lists/list-spells-classes-fighter-xphb-eldritch-knight-xphb.md "subclass=XPHB;class=XPHB"); [Bard](3-Mechanics/CLI/lists/list-spells-classes-bard.md); [Warlock (Great Old One Patron)](3-Mechanics/CLI/lists/list-spells-classes-warlock-xphb-great-old-one-patron-xphb.md "subclass=XPHB;class=XPHB"); [Cleric (Trickery Domain)](3-Mechanics/CLI/lists/list-spells-classes-cleric-xphb-trickery-domain-xphb.md "subclass=XPHB;class=XPHB"); [Druid](3-Mechanics/CLI/lists/list-spells-classes-druid.md); [Wizard](3-Mechanics/CLI/lists/list-spells-classes-wizard.md)

*Source: Player's Handbook (2024) p. 253. Available in the Free Rules (2024)*