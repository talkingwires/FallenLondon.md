---
tags:
  - Structure/Quality
qualities: [
  {name: "[[Involved in a Railway Venture]]", type: "Stories", discrete: true, unlock: "[[Advertisements of a New Venture]]", icon: "", description: "You've become a shareholder and director of the Great Hellbound Railway company"}
]
---
Here's our test!

```dataview
TABLE qualities.level as "Level", qualities.name as "Quality", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```