---
tags:
  - Storylet
  - Location/London/BazaarSideStreets
  - Character/TheManager
  - Character/SleepingMerchant
image: https://images.fallenlondon.com/icons/papers3.png
qualities:
  - name: "[[The Efficient Commissioner's Tale]]"
    level: 175
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/booksmall.png
    description: "You have obtained the help of the Manager of the Royal Beth; you can continue working on the debt in the Bazaar Side-Streets"
story: "[[The Efficient Commissioner's Tale]]"
---


You go to see the Manager in his own suite at the Royal Beth. You bring a bottle to share, and you lay out your difficulties.

"I have some responsibility here," he says heavily. "Once I was friends with the Sleeping Merchant, and out of pity and guilt I offered him too much freedom." He takes a sip of your brandy and swallows its fire.

"I will come along to help you wake him – to Parabola and to Jericho both. It is my fault that he has slept away the lives of his wife and his children and his grandchildren and all his descendants. I should be the one to face him when he wakes."

> [!onward] [[{{title}}|Onward]]


```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description" 
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```