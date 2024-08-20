---
tags:
  - Storylet
  - Estival
  - Location/London
  - Character/MrHuffam
  - Location/London/LabyrinthOfTigers
image: https://images.fallenlondon.com/icons/labyrinth.png
qualities:
  - name: "[[Of Stripes, and Coils]]"
    level: 11
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/shriek.png
    description: The Coilheart Games are coming to London
    change: Rarely does one see the news looking quite so rumpled.
---

You've walked through all the open coils. The first and second, full of beasts. The third, where men, and things that look like men, are kept in cages, and mirrors are forbidden. The fourth, where new monsters are coaxed from the bodies of the old. The fifth, where tribute is gathered for the Resplendent Court of the Wakeful Eye, and where one might buy the favours of a distant prince. You have seen the heavy gates of the Sixth Coil first-hand, and know them to be immovably shut. Until, perhaps, one day soon.

"Ahem." Not a cough, but pronounced as a word. Mr Huffam, editor of the _Unexpurgated London Gazette_, looks somewhat the worse for wear. His moustaches are rumpled, and his jacket betrays the muddy evidence of recent contact with a rather large paw.

> [!onwards] [[The Sixth, and Five Before (2)|Recall what you know of the coils]]
> The Labyrinth of Tigers exhibits beasts from all across the Unterzee. But its organising principles are as tangled as its name suggests.

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```