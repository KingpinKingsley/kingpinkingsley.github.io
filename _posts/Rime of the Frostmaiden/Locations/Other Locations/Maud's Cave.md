---
nearest-town: Easthaven
npc:
tags: location, dungeon
---

## Information
> [!infobox] +
> # Maud's Cave
> ##### Remaining Characters
> | Name | Status |
> | ---- | ---- |
> | **Fishermen** | Deceased |


Cave where the deceased fishermen (and other victims) were found dismembered. [[Maud]] would use her [[Cauldron of Plenty|cauldron]].



## Affiliated Quests
```dataview
LIST status
FROM #quest
WHERE contains(location, "Maud's Cave")
SORT session DESC
```

## Sessions Visited
```dataview
LIST session
FROM #summary
WHERE icontains(location, "Maud's Cave")
SORT session DESC
```

[[Map of The North|↩️ Return to Map]]