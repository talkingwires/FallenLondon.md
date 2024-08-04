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
    level: 11
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/shriek.png
    description: The Coilheart Games are coming to London
---

Huffam notices you noticing his dishevelment, and shakes his head. "The Keeper and his visiting dignitaries, alas, were singularly unwilling to answer my questions." He attempts to brush off the pawprint, and succeeds only in smearing it down his tweed. "Do you know, they have refused me access to the deeper coils of the Labyrinth on no less than five separate occasions? No doubt afraid of what I would see. Of what I would write."

He hands you a card. "The tigers bought out all the urchins. I am reduced to handing these out myself like a common hawker!"

Spying others about to leave the Gardens upon which he has yet to foist business cards, Huffam sketches a quick bow of goodbye. So, then; the Tiger Keeper's announcement has brought even the esteemed editor out from behind his desk.

> [!onwards] [[Start the presses|Examine the card]]
> It crumples in your hand.

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```