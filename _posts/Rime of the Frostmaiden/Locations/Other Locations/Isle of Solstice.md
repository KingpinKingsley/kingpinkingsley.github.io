---
nearest-town: 
npc: Auril
tags:
  - location
---

## Information
> [!infobox] +
> # Isle of Solstice
> ##### Remaining Characters
> | Name | Status |
> | ---- | ---- |
> | **[[Auril]]** | Alive |
> | **[[Nass]]** | Deceased |
> | **[[Söpo]]** | Alive|
> ##### Location
> | Category | Information |
> | ---- | ---- |
> | **Encounters** | List things killed |

The goddess Auril's home and the place [[Vellynne]] believes the [[Codicil of White]] can be found. Nass believed she could get the codicil without Vellynne's help and ventured to the island alone, only to die of the cold in the wilderness. Her ghost haunts the island when the party finds her (with the [[Professor Orb]] in the hand of her corpse).

There are ice sculptures of animals at various sites. These are very realistic works of art that Auril made herself.

In the center of the island is Auril's fortress named Grimskalle.

## Affiliated Quests
```dataview
LIST status
FROM #quest
WHERE contains(location, "Isle of Solstice")
SORT session DESC
```

## Sessions Visited
```dataview
LIST session
FROM #summary
WHERE icontains(location, "Isle of Solstice")
SORT session DESC
```

## Items Remaining
```dataview
LIST
FROM #item
WHERE icontains(item-location,"Isle of Solstice")
SORT file.name ASC
```

[[Map of The North|↩️ Return to Map]]