---
tags:
  - Storylet
  - Location/London
  - ExceptionalStories
image: https://images.fallenlondon.com/icons/papers3.png
qualities:
  - name: "[[Arcana]]"
    level: 
    type: Stories
    icon: https://images.fallenlondon.com/icons/tarot.png
    description: ""
story:
  - "[[Arcana]]"
---

Visitors often leave calling cards at your lodgings. Rarely, however, are such cards abstracted from an actual deck. Today you find one of the major arcana tucked between _The Hopping Post_ and an advertisement for Trompowsky et Fils. It's rather good card-stock: thick, creamy, with brilliantly gilt edges. The pigments mesmerise.


> [!choice] [[Storylets/XXII The Interloper|Inspect the tarot card]]
More striking than anything else, the central figure resembles _yourself_.


```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```