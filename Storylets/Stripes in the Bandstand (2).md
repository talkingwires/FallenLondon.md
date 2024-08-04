---
tags:
  - Storylet
  - Estival
  - Location/London
  - Character/TigerKeeper
  - Character/MrInch
image: https://images.fallenlondon.com/icons/crowd2.png
qualities:
  - name: Of Stripes, and Coils
    level: 3
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/estivaltigersmall.png
    description: A commotion in Tyrant's Gardens
---

Mr Inch steps back, and the Tiger Keeper raises himself from his pillow. "Capital. Let's start, shall we? Before our appetites grow further strained." He smiles. It is not a comforting smile. "The Prince of the Smoking Shore and Duke of all the Isles, Archipelagos and Peninsulae that were once the Sovereignty of the Humbled Satraps has seen the signs. I, His Fifth Ambassador to the Heartlands of the Messenger and Gaoler of Sins, have seen them too."

A pause. Tails swish in anticipation, but puzzlement blooms on the faces of the non-feline congregants. The Tiger Keeper turns to a compatriot. "I told you fellows, we're not on the Continent. I'll need to speak plainly; just tell the Banded Prince I said all the right things."

> [!onward] [[Tribute repaid in kind|Listen for further details]]
> The Tiger Keeper turns back the crowd. He is working up to his great point.

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```