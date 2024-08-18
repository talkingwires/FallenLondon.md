---
tags: Location/London/BoneMarket
inlineicon: https://fallenlondon.wiki/w/images/4/49/Bone17small.png
url: https://fallenlondon.wiki/wiki/The_Bone_Market
---
[[Working]]
# Bones

```dataview
TABLE rows.file.link as Name, rows.bone.value as Value, rows.bone.attributes as Attributes, rows.bone.challenge as Challenge, rows.bone.note as Note
FROM #Bone
SORT bone.value ASC
GROUP BY bone.type as Type
```


# Buyers

```dataview
TABLE rows.file.link as Name, rows.bonebuyer.likes as Likes, rows.bonebuyer.dislikes as Dislikes, rows.bonebuyer.primary_reward as Primary, rows.bonebuyer.secondary_reward as Secondary, rows.bonebuyer.primary_formula as PF, rows.bonebuyer.secondary_formula as SF
FROM #Vendor/BoneMarket 
```




# Perineal Buyers


| Buyer                                                                                                 | Primary Reward               | Primary Scaling  | Secondary Reward              | Secondary Scaling                                       | Requires                             | Notes    |
| ----------------------------------------------------------------------------------------------------- | ---------------------------- | -------------------------- | ----------------------------- | --------------------------------------------- | ------------------------------------ | --- |
| [[Sell a complete skeleton to the Bone Hoarder\|Palaeontologist with Hoarding Propensities]]          | [[Bone Fragments]]           | Value\*5+1 | [[Unearthly Fossil\|Unearthly Fossils]] | Always 2                                      |                                  |     |
| [[Sell your Skeleton to a Naive Collector\|A Naive Collector]]                                        | [[Thirsty Bombazine Scrap]]  | Value/250         |                                  |                                               | [[Suspicion]] < 4                    |     |
| [[Sell your Skeleton to the Sculptress\|A Familiar Bohemian Sculptress]]                              | [[Preserved Surface Blooms]] | Value/250+4       | [[Rumour of the Upper River]]    | Support for Counter-church Theology | [[Respectable]] 0<br>[[Antiquity]] 0 | No [[Antiquity]]    |
| [[Sell your skeleton to a Pedagogically Inclined Grandmother\|A Pedagogically Inclined Grandmother]]  | [[Incisive Observation\|Incisive Observations]]  | Value/50+20                                 |                               |                                               | [[Dreaded]] 0<br>[[Menace]] 0 | No [[Menace]] |
| [[Sell your Skeleton to the Theologian of the Old School\|Theologian of the Old School]]     | [[Crate of Incorruptible Biscuits]]  |  Value/250+4       |                                  |                                               |                                      | No [[Amalgamy]] |
| An Enthusiast of the Ancient World                                                        |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |
|                                                                                              |                              |                            |                               |                                               |                                      |     |

# Skeleton Requirements

|Animal|Torso|Skulls|Arms|Legs|Wings|Fins|Tails|Tentacles|Mania Bonus|
| ------ | ----- | ------ | ---- | ---- | ----- | ---- | ----- | --------- | ----------- |
|Chimera|Any|Any|Any|Any|Any|Any|Any|Any||
|Humanoid|[[Headless Skeleton]] <br> [[Human Ribcage]] <br> [[Thorned Ribcage]]|1|2|2|0|0|0|Any||
|Ape|[[Headless Skeleton]] <br> [[Human Ribcage]] <br> [[Thorned Ribcage]]|1|4|0|0|0|0|Any||
|Monkey|[[Headless Skeleton]] <br> [[Human Ribcage]] <br> [[Thorned Ribcage]]|1|4|0|0|0|1|Any||
|Bird|[[Segmented Ribcage]] [[Thorned Ribcage]] [[Flourishing Ribcage]] [[Skeleton with Seven Necks]] [[Mammoth Ribcage]] [[Ribcage with a Bouquet of Eight Spines]] [[Prismatic Frame]] [[Leviathan Frame]] [[Glim-Encrusted Carapace]]|Any|0|2|2|0|0-1|Any|10%|
|Amphibian|[[Segmented Ribcage]] [[Thorned Ribcage]] [[Flourishing Ribcage]] [[Skeleton with Seven Necks]] [[Mammoth Ribcage]] [[Ribcage with a Bouquet of Eight Spines]] [[Prismatic Frame]] [[Leviathan Frame]] [[Glim-Encrusted Carapace]]|1|0|4|0|0|0|Any|10%|
|Reptile|[[Segmented Ribcage]] [[Thorned Ribcage]] [[Flourishing Ribcage]] [[Skeleton with Seven Necks]] [[Mammoth Ribcage]] [[Ribcage with a Bouquet of Eight Spines]] [[Prismatic Frame]] [[Leviathan Frame]] [[Glim-Encrusted Carapace]]|1|0|0-4|0|0|1|Any|10%|
|Fish|[[Segmented Ribcage]] [[Thorned Ribcage]] [[Flourishing Ribcage]] [[Skeleton with Seven Necks]] [[Mammoth Ribcage]] [[Ribcage with a Bouquet of Eight Spines]] [[Prismatic Frame]] [[Leviathan Frame]] [[Glim-Encrusted Carapace]]|1|0|0|0|2+|0-1|Any|15%|
|Insect|[[Segmented Ribcage]] [[Thorned Ribcage]] [[Flourishing Ribcage]] [[Skeleton with Seven Necks]] [[Mammoth Ribcage]] [[Ribcage with a Bouquet of Eight Spines]] [[Prismatic Frame]] [[Leviathan Frame]] [[Glim-Encrusted Carapace]]|1|0|6|0-4|0|0|Any|15%|
|Spider|[[Segmented Ribcage]] [[Thorned Ribcage]] [[Flourishing Ribcage]] [[Skeleton with Seven Necks]] [[Mammoth Ribcage]] [[Ribcage with a Bouquet of Eight Spines]] [[Prismatic Frame]] [[Leviathan Frame]] [[Glim-Encrusted Carapace]]|0|0|8|0|0|0-1|Any|15%|
|Curator|[[Segmented Ribcage]] [[Thorned Ribcage]] [[Flourishing Ribcage]] [[Skeleton with Seven Necks]] [[Mammoth Ribcage]] [[Ribcage with a Bouquet of Eight Spines]] [[Prismatic Frame]] [[Leviathan Frame]] [[Glim-Encrusted Carapace]]|1|2|2|2|0|0|Any|N/A|


# Recipes

[[ Amalgamous Amphibians]]
[[Amalgamous Birds]]
[[Antique Insects]]
[[Antique Reptiles]]
[[Antique Birds]]
[[Menacing Amphibians]]
[[Amalgamous Insects]]
[[Amalgamous Reptiles]]
[[Menacing Fish]]
[[Using up human ribcages and horned skulls]]
[[Survey Monkey]]
[[Bessemer Grinding]]
[[Bird of Brass and Bone]]