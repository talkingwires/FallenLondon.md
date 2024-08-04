---
tags:
  - Storylet
  - Estival
  - Location/London
  - Character/TigerKeeper
  - Character/MrInch
image: https://images.fallenlondon.com/icons/papers3.png
qualities: [
  {name: "Of Stripes, and Coils", level: 2, type: "Stories", discrete: true, unlock: "", icon: "https://images.fallenlondon.com/icons/estivaltigersmall.png", description: "A commotion in Tyrant's Gardens"}
]
story: "Of Stripes, and Coils"
---

Tyrant's Gardens is awash with people. Many hold the peculiar vellum scrolls that invited you here; others seem to have simply followed the crowds. Word travels fast, and, in the languid humidity of false-summer, London is easily tempted by distraction.

And what a distraction this is. On the edge of the park, in view of the Labyrinth, is the bandstand. The crowd has formed a sort of perimeter around it, leaving a thin strip of empty lawn between themselves and the bandstand's occupants.

For the bandstand and its immediate area are _replete_ with tigers. They loll on jaundiced grass and lounge on velvet pillows. They chuff on fragrant pipes and examine their claws. They stretch out their paws, and yawn hugely. (A yawn, for a tiger, is a full-body experience, one that begins at the tail and ends at the teeth, endeavouring to exhibit as many deadly muscles and claws as it can. A yawn, for a tiger, is a form of threat.)

At the heart of the bandstand, occupying a futon the size of a string section, is a tiger in an emerald velvet smoking cap. And beside him stands Mr Inch – zoologist, beast-trainer, and the only human within this stripy inner circle.

> [!choice] [[Poking the tiger|Jostle for position]]
> Whatever is about to happen, it behoves you to get a good view.

> [!choice] [[unknownHang back]]
> You don't want to be _too_ close to the front. These are tigers, after all.

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```