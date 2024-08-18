---
tags:
  - Quality
---

```dataview
TABLE qualities.level as "Level", qualities.name as "Quality", qualities.description as "Description" , qualities.change as "Change Text" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
SORT qualities.level ASC
```