---
tags: Structure
---

```dataview
TABLE qualities.level as "Level", qualities.name as "Quality", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name)
FLATTEN qualities
```

```dataview
LIST 
WHERE qualities
SORT qualities.level ASC
FLATTEN qualities.name AS groups GROUP BY groups
```