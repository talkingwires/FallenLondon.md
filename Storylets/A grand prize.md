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
    level: 10
    type: Stories
    discrete: true
    unlock: ""
    icon: https://images.fallenlondon.com/icons/shriek.png
    description: The Coilheart Games are coming to London
    change: London is abuzz with the news.
---

The roar of a tiger's approval is a terrible thing to behold, being similar in almost all respects to a roar of bloody murder, and therefore taking the form of a ferocious baring of fang and gum and gullet. People begin to clap and whoop, caught up in the excitement or eager to be seen to agree with their feline compatriots.

You add your voice to theirs, cheering and hooting at the bandstand. The Tiger Keeper nods, raising a placatory paw. From somewhere nearby, a child in a blue doublet rushes to his side to pack and light an ebony pipe. The crowd quiets, slowly, while the Keeper puffs.

"The tournament will be held in the Labyrinth. We shall construct the amphitheatres anon. Expect the foreign delegations to arrive in due course – and then the games may begin."

As one the tigers stretch, stand, and pad off in the direction of the Labyrinth. As they leave, one question hovers on the lips of the assembled Londoners. A tournament is all very well. But what is the prize? What, exactly, is in the Sixth Coil?

> [!onwards] [[The Sixth, and Five Before|Onwards]]
> It sounds exciting. And you don't want any of the tigers to catch you _not_ cheering.

```dataview
TABLE WITHOUT ID qualities.name as "Quality", qualities.level as "Level", qualities.description as "Description", qualities.change as "Change"  
WHERE contains(file.frontmatter.qualities.name, this.file.name) or file.name = this.file.name 
FLATTEN qualities
```