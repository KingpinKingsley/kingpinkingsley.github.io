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

## About Velys
> [!infobox] +
> # Velys
> ![[Image.png | cover hsmall]]
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Player Character |
> | **Status** | Alive |
> | **Race** | Goliath |
> | **Level** | 5 |
> | **Likes** | {Likes} |
> | **Dislikes** | {Dislikes} |
> | **Strengths** | {Strengths} |
> | **Weaknesses** | {Weaknesses} |
> ##### Campaign
> | Category | Information |
> | ---- | ---- |
> | **Class(es)** | Cleric |
> | **Subclass(es)** | Life Domain |
> | **Alignment** | {Alignment} |
> | **Affiliation** | {Affiliation} |
> ##### Other
> | Category | Information |
> | ---- | ---- |
> | **Player** | {Player} |

{Text}

## Observations / Trivia
{Text}

## Niles
- A healer and a man of learning. He's glad to have someone who specializes in healing in the group, but is now starting to realize that Velys will probably never be good at being stealthy in a high stakes situation, and that may be a detriment.
- Quick to heal even an inmate during interrogation. Deep down Velys is caring, but not caring enough to dissent to torture.
- Reliable and can be trusted to do his job in tough moments. Kept everyone alive during the siege of Xardorok's fortress.
- Is much too smug, even in serious moments. When everyone started going missing during the Trial of Isolation, Velys was too calm.

## Items

```dataview
LIST
FROM #item
WHERE icontains(current-holder,"Velys")
SORT file.name ASC
```

## Session
```dataview
TABLE session AS Session
FROM #summary
WHERE icontains(player,"Velys")
SORT session DESC
```