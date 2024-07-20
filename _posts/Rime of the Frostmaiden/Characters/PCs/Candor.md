---
allies: 
enemies: 
affiliation: 
status: Alive
tags:
  - player
  - party
  - character
---

> [!quote] *A text quote or something.*

## About Candor
> [!infobox] +
> # Candor
> ![[Image.png | cover hsmall]]
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Player Character |
> | **Status** | Alive |
> | **Race** | Tiefling |
> | **Level** | 5 |
> | **Likes** | {Likes} |
> | **Dislikes** | {Dislikes} |
> | **Strengths** | {Strengths} |
> | **Weaknesses** | An unhealthy attachment to people |
> ##### Campaign
> | Category | Information |
> | ---- | ---- |
> | **Class(es)** | Barbarian |
> | **Subclass(es)** | Path of Wild Magic |
> | **Alignment** | Chaotic Edgelord |
> | **Affiliation** | Harpers Guild |
> ##### Other
> | Category | Information |
> | ---- | ---- |
> | **Player** | {Player} |

As a teen, Candor realized on morning that he was not the biological son of his parents when he started growing bumps (which would eventually become his Tiefling horns). In the conversation with his parents while at the breakfast table, his mother implied that he had been left on their doorstep as a baby, and so he is adopted. Candor loses his temper and his wild magic surfaces, blowing a hole into the side of their home.

## Relationships
Below are the most relevant/important relationships to this character.

[[Candor's Mom|Mom]] / [[Candor's Dad|Dad]]. Candor's adoptive parents.

## Niles
- The other problem child that causes issues in some situations. Niles thinks Candor may have attachment issues stemming from not having friends, so he immediately found kindship with some of the worst people ([[Avarice]], [[Dzaan]]) possible. Although, Niles did notice when Candor actually [[The Ferry|asked]] whether the group was going to kill or talk with the Duergar.

## Items

```dataview
LIST
FROM #item
WHERE icontains(current-holder,"Candor")
SORT file.name ASC
```

## Session
```dataview
TABLE session AS Session
FROM #summary
WHERE icontains(player,"Candor")
SORT session DESC
```