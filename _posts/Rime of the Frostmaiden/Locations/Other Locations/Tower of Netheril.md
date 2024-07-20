---
nearest-town: 
npc: 
tags:
  - location
---

## Information
> [!infobox] +
> # Tower of Netheril
> ##### Remaining Characters
> | Name | Status |
> | ---- | ---- |
> | **Name** | {Status} |
> | **Name** | {Status} |
> ##### Travel Time (Hours)
> | Category | Walking | Sled |
> | ---- | ---- | ---- |
> | **Bremen** | {Hours} | {Hours} |
> | **Bryn Shander** | {Hours} | {Hours} |
> | **Caer-Dineval** | {Hours} | {Hours} |
> | **Caer-Konig** | {Hours} | {Hours} |
> | **Dougan's Hole** | {Hours} | {Hours} |
> | **Easthaven** | {Hours} | {Hours} |
> | **Good Mead** | {Hours} | {Hours} |
> | **Lonelywood** | {Hours} | {Hours} |
> | **Targos** | {Hours} | {Hours} |
> | **Termalaine** | {Hours} | {Hours} |
> ##### Affiliated Quests
> | Title | Status |
> | ---- | ---- |
> | **Title** | {Status} |




## Affiliated Quests
```dataview
LIST status
FROM #quest
WHERE contains(location, "Tower of Netheril")
SORT session DESC
```

## Sessions Visited
```dataview
LIST session
FROM #summary
WHERE icontains(location, "Tower of Netheril")
SORT session DESC
```

[[Map of The North|↩️ Return to Map]]