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

## About Gaspard
> [!infobox] +
> # Disappeared Dad
> ![[Gaspard.jpg| cover hsmall]]
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
> | **Class(es)** | Fighter |
> | **Subclass(es)** | Samurai |
> | **Alignment** | Lawful Awful |
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
WHERE icontains(current-holder,"Gaspard")
SORT file.name ASC
```

## Session
```dataview
TABLE session AS Session
FROM #summary
WHERE icontains(player,"Gaspard")
SORT session DESC
```