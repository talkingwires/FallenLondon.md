---
tags:
  - Storylet
  - Estival
  - Location/London
  - Character/TigerKeeper
image: https://images.fallenlondon.com/icons/crowd2.png
qualities: [
  {name: "[[Of Stripes, and Coils]]", level: 3, type: "Stories", discrete: true, unlock: "", icon: "https://images.fallenlondon.com/icons/estivaltigersmall.png", description: "A commotion in Tyrant's Gardens",  change: "What do they all want? Quickly now, before someone gets eaten."}
]
story: "Of Stripes, and Coils"
---

Already, urchins and opportunists are making the most of the crowds, selling blankets and stolen chairs to those unwilling to soil their day-clothes. You claim a temporarily vacated spot, and bribe an urchin to keep its previous occupant away. She winks, and lifts her cap.

This close, you can smell the tigers: musk, and meat, and hookah smoke. A few feet away, a man with very red cheeks shuffles his steamer chair backwards. "I say, are we sure that it's safe here without any cages?"

The tigers in earshot freeze. A nearby woman gasps, and drops her fan. A growl bubbles by the bandstand, and commutes through the throats of each assembled feline.

Mr Inch coughs, glaring at the offending speaker. "Not to worry, good sir. I shall be escorted back into my enclosure in good time, and I solemnly swear not to maim you in the interim. No matter how tempting it may be." An uneasy chuckle passes through the crowd. In a tiger's throat, a chuckle and a growl are not so different – but the predator's stillness leaves their frames.

> [!onward] [[Stripes in the Bandstand (2)]]
> Whatever is about to happen, it behoves you to get a good view.

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```