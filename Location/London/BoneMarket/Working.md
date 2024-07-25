 Bat Wing 	1  	1 Monstrous Anatomy
Difficulty increases by 2 for every fin 	-1 x Menace
0-2 x Self-Evident Implausibility

![[Helical Thighbone#Attributes]]


```dataview
TABLE rows.file.link, rows.bone.type, rows.bone.value, rows.bone.challenge, rows.bone.attributes
FROM #Bone
SORT bone.value ASC
GROUP BY bone.type
```


```dataview
LIST rows.file.link
FROM #Location/London/BoneMarket 
where file.name != this.file.name
GROUP BY file.folder
```

```dataview
TABLE WITHOUT ID this
WHERE file = this.file 
```