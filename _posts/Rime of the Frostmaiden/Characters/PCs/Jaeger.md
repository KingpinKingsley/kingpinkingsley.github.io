---
allies: Broomson Family
enemies: 
affiliation: 
status: Alive
tags:
  - player
  - party
  - character
---

> [!quote] *A text quote or something.*

## Information
> [!infobox] +
> # Jaeger Broomson
> ![[Jaeger.jpg| cover hsmall]]
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Player Character |
> | **Status** | Alive |
> | **Race** | Human |
> | **Level** | 5 |
> | **Likes** | Tinkering |
> | **Dislikes** | Considering dangerous situations |
> | **Strengths** | Intellectual Endeavors |
> | **Weaknesses** | Non-Intellectual Endeavors |
> ##### Campaign
> | Category | Information |
> | ---- | ---- |
> | **Class(es)** | Artificer |
> | **Subclass(es)** | Artillerist |
> | **Alignment** | Chaotic Pitiable |
> | **Affiliation** | Harpers Guild |
> ##### Other
> | Category | Information |
> | ---- | ---- |
> | **Player** | {Player} |

Around the age of 15, while hunting with his father in the jungle near their home, Jaeger shot his crossbow and struck a boar in the heart. To his surprise, the boar transformed into a panicking human man, searching his surroundings for the location of his attacker. Behind him, Jaeger's father commands the boy to keep shooting, implying that he wants the mysterious human dead. Jaeger is too shocked to listen or react before the human begins running away. His father then pulls out his own crossbow and kills the man by shooting him through the head.

Favorite color is orange. It's the color he turns his gun barrel when he casts Light, promptly alerting all aberrations in the room.

## Relationships
Below are the most relevant/important people to this character.

- [[Jaeger's Father]]
- [[Ryker]]

## Niles
- Originally believing Jaeger to be the poster child of bad calls, Niles has come to understand the man who constantly puts the party in danger. Whether it's initiating a fight with Sephek, sparking an impromptu battle with a yeti while no one else knows the plan, or alerting an entire stronghold of their location... Niles takes solace in known that outside of these situations Jaeger means well.

## Items
The following is a list of associated items:

```dataview
LIST
FROM #item
WHERE icontains(current-holder,"Jaeger")
SORT file.name ASC
```

## Session
```dataview
TABLE session AS Session
FROM #summary
WHERE icontains(player,"Jaeger")
SORT session DESC
```