---
tags:
  - Storylet
  - Location/
  - Character/
image: https://images.fallenlondon.com/icons/papers3.png
qualities: [
  {name: "", level: , type: "Stories", discrete: true, unlock: "", icon: "", description: ""}
]
story: ""
---


> [!choice] [[{{title}}|Choice]]

> [!onward] [[{{title}}|Onward]]


```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```