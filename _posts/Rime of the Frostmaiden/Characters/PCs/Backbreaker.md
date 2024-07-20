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

> [!quote] *A humble Chad that speaks of his Gram-Gram’s stories and has a hard time being mean.*

## About Backbreaker
> [!infobox] +
> # Soft-Spoken Behemoth
> ![[Image.png | cover hsmall]]
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Player Character |
> | **Status** | Alive |
> | **Race** | Bugbear |
> | **Level** | 5 |
> | **Likes** | {Likes} |
> | **Dislikes** | {Dislikes} |
> | **Strengths** | {Strengths} |
> | **Weaknesses** | {Weaknesses} |
> ##### Campaign
> | Category | Information |
> | ---- | ---- |
> | **Class(es)** | Barbarian |
> | **Subclass(es)** | Path of the Storm Herald |
> | **Alignment** | Chaotic Peaceful |
> | **Affiliation** | Harper's Guild |
> ##### Other
> | Category | Information |
> | ---- | ---- |
> | **Player** | {Player} |

Served as the intern to a [[Sherlock Gnomes|famous investigator]] in a case solve the case of missing diamonds. While chasing the culprits, Backbreaker uses too much force behind his attack and breaks the walkway he, the culprit, and his mentor are standing on. While he manages to escape, Backbreaker dooms the investigator to a long fall.

## Relationships
Below are the most relevant/important relationships to this character.

[[Sherlock Gnomes]]. A mentor from Backbreaker's days as an intern.

## Niles
- Niles feels as though he owes Backbreaker for saving him from death twice. The first time during the fight with [[Sephek]] in Bryn Shander, and the second when the avalanche washed over them at Kelvin's Cairn. Niles may have shown a lot of favoritism towards Backbreaker in the days following.
- Backbreaker's uncannily bad luck has led to Niles looking out for him more than necessary.
- In a tense moment before going to the Trial of Cruelty, Backbreaker is the first to back up Niles when the group needs to consider their next steps.


## Items

```dataview
LIST
FROM #item
WHERE icontains(current-holder,"Backbreaker")
SORT file.name ASC
```

**Previously:**

```dataview
LIST
FROM #item
WHERE icontains(previous-holder,"Backbreaker")
SORT file.name ASC
```

## Session
```dataview
TABLE session AS Session
FROM #summary
WHERE icontains(player,"Backbreaker")
SORT session DESC
```