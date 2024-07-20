---
nearest-town: Good Mead
npc: Unknown Hero
tags: location
---

## Information
> [!infobox] +
> # Unknown Hero's Tomb
> ##### Remaining Characters
> | Name | Status |
> | ---- | ---- |
> | **[[Unknown Hero]]** | Deceased |
> | **[[Ogre Friend]]** | Deceased |
> | **[[Duhg's Other Friend]]** | Deceased |
> ##### Location
> | Category | Information |
> | ---- | ---- |
> | **Located in** | [[Duhg's Cave]] |
> | **Encounters** | [[Duhg\|1]], [[Ogre Friend\|2]], [[Duhg's Other Friend\|3]] |

The tomb houses an ancient hero with three cursed magic items, consisting of a [[Augur's Dagger|Dagger]], [[Pearl of Power|Pearl Necklace]], and [[Wand of the War Mage|Wand]].


## Affiliated Quests
```dataview
LIST status
FROM #quest
WHERE contains(location, "Unknown Hero's Tomb")
SORT session DESC
```

## Sessions Visited
```dataview
LIST session
FROM #summary
WHERE icontains(location, "Unknown Hero's Tomb")
SORT session DESC
```


## Items Remaining
```dataview
LIST
FROM #item
WHERE icontains(item-location,"Unknown Hero's Tomb")
SORT file.name ASC
```

[[Map of The North|↩️ Return to Map]]