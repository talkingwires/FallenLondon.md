---
tags:
  - Storylet
  - Location/
  - Character/
image: https://images.fallenlondon.com/icons/papers3.png
qualities:
  - name: "[[The Efficient Commissioner's Tale]]"
    level: 40
    type: Stories
    discrete: true
    unlock: "[[The Efficient Commissioner's Tale]] 40"
    icon: https://fallenlondon.wiki/w/images/f/f3/Book.png
    description: The Efficient Commissioner has interrupted the other work of the GHR
story: "[[The Efficient Commissioner's Tale]]"
---
The chunk of stone sits on the table before you. Everyone has cleared to give you as much space as they're able, considering the size of the room. This is still quite limited.

The boardroom, you note, manages to accommodate however many people crowd into it, but always tightly enough that everyone is jostling a neighbour with their elbows. Truly Infernal design.

> [!choice] [[Not poisonous|Study its likely chemical effects on the Bazaar]]
> If the Bazaar were to consume this message, what would happen?

> [!choice] [[Without equipment Here|Discover its age and its kinship to stars]]
> What has the Red Science to say about it?

> [!choice] [[The Creditor's calling card|Search it for letters of fire]]
> Is it inscribed?

> [!onward] [[Posted from the Brass Embassy|Repackage this item and send it on to the Bazaar]]
> Jervaise is waiting. The Bazaar will know it is on its way.


```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```