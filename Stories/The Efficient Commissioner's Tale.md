---
tags:
  - Quality
image: 
qualities: [
  {name: "[[The Efficient Commissioner's Tale]]", level: , type: "Stories", discrete: true, unlock: "", icon: "", description: ""}
]
story: ""
---

```dataview
TABLE qualities.level as "Level", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name)
SORT qualities.level ASC
```