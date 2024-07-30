---
tags:
  - Storylet
  - Location/London/MolochStreet
  - Character/Masters/MrSpices
  - Character/Bazaar
image: https://images.fallenlondon.com/icons/honeyjar.png
qualities:
  - name: "[[The Efficient Commissioner's Tale]]"
    level: 100
    type: Stories
    discrete: true
    unlock: "[[The Efficient Commissioner's Tale]] 100"
    icon: https://fallenlondon.wiki/w/images/f/f3/Book.png
    description: Those trying to rescue the Bazaar meet in the Bazaar Side-Streets
story: "[[The Efficient Commissioner's Tale]]"
---

The Efficient Commissioner lays the stone in its wrapping paper again and ties it up. She is gentler than she would need to be if she were merely packing up a piece of masonry.

"I think we had better see it delivered ourselves," she says. "Don't you?" The Masters are already rising from their positions, the neddy men clearing their way.

"What about us?" asks the Board Secretary.

"You're free to go home," says the Efficient Commissioner, over her shoulder.

"Yes, but – is London going to be drowned in lacre? Are our souls going to be fed to Hell? Will we have to take refuge in Parabola?" The Secretary has stood up too, and he looks like he might leave his notes on the table and chase after her.

"We can't all parade into the Bazaar," says the Commissioner, exasperated. It plainly did not occur to her that some other members of the board might take up this quest as well. She points at you. "I can take one director along. The one I deem most likely to be of use. The rest of you will have to await a report, I'm afraid."

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```