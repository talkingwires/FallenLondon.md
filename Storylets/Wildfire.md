---
tags:
  - Storylet
  - Estival
  - Location/London
  - Location/London/LabyrinthOfTigers
image: https://images.fallenlondon.com/icons/fist.png
qualities:
  - name: Of Stripes, and Coils
    level: 20
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/misterhuffam.png
    description: The Coilheart Games are coming to London
    change: London hums with speculation.
---

You visualise the path before you. You don't need to know what the treasure is to want it – so often, desire cares not for the facts. The people you meet on the way home don't want facts either, not really – just gossip. You have countless permutations of the same conversation as you walk home, and word spreads with you. You, after all, were there. You heard the words right from the tiger's mouth.

What is happening? Who is coming? What does it mean? And, above all, what could possibly be contained within the Sixth Coil to be worth all of this vast and extravagant expense? You stride through the streets, determined to do what you must. The city effervesces in your wake.













```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```