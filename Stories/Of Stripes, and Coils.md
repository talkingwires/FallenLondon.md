---
tags:
  - Quality
---

```dataview
TABLE qualities.level as "Level", qualities.name as "Quality", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```