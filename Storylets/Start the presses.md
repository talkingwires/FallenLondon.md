---
tags:
  - Storylet
  - Estival
  - Location/London
  - Character/MrHuffam
  - Location/London/LabyrinthOfTigers
image: https://images.fallenlondon.com/icons/labyrinth.png
qualities:
  - name: Of Stripes, and Coils
    level: 15
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/misterhuffam.png
    description: The Coilheart Games are coming to London
    change: The venerable Mr Huffam seems to think there's a story here.
---

It is more like notepaper than card stock, and handwritten to boot. Has Huffam been penning these on the move? You spy him in the crowd again, and note the sweat trickling down the back of his collar. The old man looks out of breath. News, after all, travels fast – so it only follows that a good journalist should be able to move faster.

_'INFORMATION WANTED: What's in the SIXTH COIL?'  
Good MONEY Paid for SOLID & PUBLISHABLE Leads!  
Report EXCLUSIVELY to the Offices of the _GAZETTE_.'_

The loping cursive lists the address of the office, and an exhortation for the reader to help shine the 'revealing light of journalism' upon London. As you leave the gardens, Huffam's card crumpled in your hand, you find that the rumour mill has already outpaced you.

> [!onwards] [[A Tournament on the Horizon|Onwards]]
> It crumples in your hand.

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```