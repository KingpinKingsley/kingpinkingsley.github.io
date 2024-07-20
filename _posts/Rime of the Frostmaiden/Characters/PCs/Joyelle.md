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

## About Joyelle
> [!infobox] +
> # Animal Supremacist
> ![[Image.png | cover hsmall]]
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Player Character |
> | **Status** | Alive |
> | **Race** | Tabaxi |
> | **Level** | 5 |
> | **Likes** | Non-humanoids, clearly |
> | **Dislikes** | Interacting with humanoids, clearly |
> | **Strengths** | {Strengths} |
> | **Weaknesses** | {Weaknesses} |
> ##### Campaign
> | Category | Information |
> | ---- | ---- |
> | **Class(es)** | Druid |
> | **Subclass(es)** | Circle of the Moon |
> | **Alignment** | Chaotic Biased |
> | **Affiliation** | Emerald Conclave |
> ##### Other
> | Category | Information |
> | ---- | ---- |
> | **Player** | {Player} |

{Text}

## Observations / Trivia
{Text}

## Niles
- Niles respects Joyelle for her observant nature. He sees a peer when it comes to traversing and surviving nature. He just wishes that she would speak with the group a little more and make her presence known. Also, the blatant preference of woodland creatures over people has been odd to him, but he doesn't say anything.



## Items
```dataview
LIST
FROM #item
WHERE icontains(current-holder,"Joyelle")
SORT file.name ASC
```

## Sessions
```dataview
TABLE session AS Session
FROM #summary
WHERE icontains(player,"Joyelle")
SORT session DESC
```