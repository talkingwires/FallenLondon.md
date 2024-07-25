---
tags:
  - Structure
---

```dataview
LIST
FROM "Locations"
```

```dataview
LIST 
FROM "Gains"
```

```dataview
LIST 
FROM "Gains"
```

```dataview
LIST 

WHERE contains(qualities, "Ambition - Heart's Desire")
SORT file.name ASC
```

```dataview
LIST 
FROM #Gains

SORT file.name ASC
```

```dataview
LIST rows.file.link
FROM [[Making Waves]]
FLATTEN file.etags AS tags GROUP BY tags
```

```dataview
LIST rows.file.link
WHERE gains
FLATTEN gains AS groups GROUP BY groups
```