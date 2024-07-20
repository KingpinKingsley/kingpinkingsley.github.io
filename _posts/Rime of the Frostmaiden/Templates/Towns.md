---
locations:
travel-bremen:
travel-bryn: 
travel-dineval:
travel-konig:
travel-dougan: 
travel-easthaven:
travel-good:
travel-lonelywood:
travel-targos:
travel-termalaine:
tags: town, location
---

## Information
> [!infobox] +
> # {{title}}
> ![[Image.png| cover hsmall]]
> ##### Notable Characters
> | Name | Status |
> | ---- | ---- |
> | **Speaker** | {Status} |
> | **Sheriff** | {Status} |
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


### Locations and Locals

###### **FIRST**


## Quests

```dataview
LIST status
FROM #quest
WHERE contains(town,"{{title}}")
SORT session DESC
```

## Sessions

```dataview
LIST session
FROM #summary
WHERE contains(location, "{{title}}")
SORT session DESC
```

## Map
![[{{title}} Map.jpg|800]]

[[Map of The North|↩️ Return to Map]]