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

## About Mori
> [!infobox] +
> # Mori
> ![[Mori.png| cover hsmall]]
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Player Character |
> | **Status** | Alive |
> | **Race** | Human |
> | **Level** | 5 |
> | **Likes** | {Likes} |
> | **Dislikes** | {Dislikes} |
> | **Strengths** | {Strengths} |
> | **Weaknesses** | {Weaknesses} |
> ##### Campaign
> | Category | Information |
> | ---- | ---- |
> | **Class(es)** | Warlock |
> | **Subclass(es)** | The Fiend |
> | **Alignment** | {Alignment} |
> | **Affiliation** | {Affiliation} |
> ##### Other
> | Category | Information |
> | ---- | ---- |
> | **Player** | {Player} |

{Text}

## Observations / Trivia
{Text}

## Relationships
Below are the most relevant/important relationships to this character.

#### Allies



#### Acquaintances



#### Other Characters


## Items
```dataview
LIST
FROM #item
WHERE icontains(current-holder,"Mori")
SORT file.name ASC
```

## Sessions
```dataview
TABLE session AS Session
FROM #summary
WHERE icontains(player,"Mori")
SORT session DESC
```