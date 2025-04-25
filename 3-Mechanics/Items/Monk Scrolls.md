---
obsidianUIMode: preview
cssclasses:
  - json5e-item
tags:
  - item
aliases: 
SourceType: Item
NoteIcon: item
BookSource:
---

<%*
const hasTitle = !tp.file.title.startsWith("NewMagicItem");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Item Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


# Historical Scrolls
Scrolls obtained from the monk monastery that speak to the history of the monastery, the heart, and Vuremodor.

Description

*Source: SourceName*