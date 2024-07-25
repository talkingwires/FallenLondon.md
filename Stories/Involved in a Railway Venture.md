---
tags:
  - Quality
qualities: [
  {name: "[[Involved in a Railway Venture]]", type: "Stories", discrete: true, unlock: "[[Advertisements of a New Venture]]", icon: "", description: "While Lord Mayor, Virginia made it possible to build west. London is taking advantage!"}
]
---
Here's our test!

```dataview
TABLE qualities.level as "Level", qualities.name as "Quality", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```