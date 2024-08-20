---
tags:
  - Storylet
  - Estival
  - Location/London
  - Character/TigerKeeper
image: https://images.fallenlondon.com/icons/papers3.png
qualities: [
  {name: "[[Of Stripes, and Coils]]", level: 2, type: "Stories", discrete: true, unlock: "", icon: "https://images.fallenlondon.com/icons/estivaltigersmall.png", change: "Tigers, beast-tamer, and Tiger Keeper. Not your usual picnic.", description: "A commotion in Tyrant's Gardens"}
]
story: "Of Stripes, and Coils"
---

You seek out the Tiger Keeper's gaze. Usually when you meet, it is in a cloud of hookah smoke, and his affect languid and careless. But today his lambent eyes are alert. Whatever is about to happen, it has his full and undivided attention. He blinks at you once, slowly, in acknowledgement.

> [!onward] [[Stripes in the Bandstand|Onward]]


```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```