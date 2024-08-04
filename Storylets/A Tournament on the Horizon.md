---
tags:
  - Storylet
  - Estival
  - Location/London
  - Character/MrHuffam
  - Location/London/LabyrinthOfTigers
image: https://images.fallenlondon.com/icons/centuryexibition.png
qualities:
  - name: Of Stripes, and Coils
    level: 15
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/misterhuffam.png
    description: The Coilheart Games are coming to London
---

The Coilheart Games. The ever-sealed Sixth Coil, and the prize within. The news prowls the city, dominates discussion. As you make your way back towards your Lodgings, you hear the Tiger Keeper's pronouncement echoed in alleyways, under eaves, upon the lips of the great, the good, the shabby and the unwashed. No wonder Huffam is angling for an exclusive.

With information so thin on the ground, gossip turns to speculation. Acquaintances grab you on the street. "Have you heard the news?" "What do you think?" "How are you feeling?"

> [!choice] [[Express excitement]]
> New visitors! The spirit of competition! A city, filled to bursting with peoples of all kinds and creeds! The prospect is intoxicating.

> [!choice] [[Show a modicum of caution]]
> Summer is a dangerous time in the Fifth City. And, lest you forget, these are _tigers_. A little wariness is only sensible.

> [!choice] [[Wildfire|Exhibit unshakeable determination]]
> Competitions mean winners. Whatever is in the Sixth Coil of the Labyrinth, it seems to be a grand prize indeed – and you want a part of it.

> [!choice] [[Affect disinterest]]
> A grand and unknown event may be taking over the city – but it will not drag _you_ in its wake. You have things to do. Probably.












```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```