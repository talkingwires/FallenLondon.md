---
tags:
  - Storylet
  - Estival
  - Location/London
  - Location/London/LabyrinthOfTigers
image: https://images.fallenlondon.com/icons/labyrinth.png
qualities:
  - name: Of Stripes, and Coils
    level: 10
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/shriek.png
    description: The Coilheart Games are coming to London
---

With the tigers gone, there is little reason to remain in Tyrant's Gardens except to gossip, or ask questions. All chatter is turned towards the topic of the tournament, of the Labyrinth of Tigers, and the Sixth Coil that lurks within.

> [!onwards] [[Labyrinthine|Recall what you know of the coils]]
> The Labyrinth of Tigers exhibits beasts from all across the Unterzee. But its organising principles are as tangled as its name suggests.

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```