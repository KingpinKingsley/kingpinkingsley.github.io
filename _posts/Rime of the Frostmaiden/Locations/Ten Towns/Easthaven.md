---
locations: White Lady Inn, Wet Trout Tavern, Easthaven Town Hall
alias: White Lady Inn, Wet Trout Tavern, Easthaven Town Hall
travel-bremen: 12.5 hours
travel-bryn: 7.5 hours
travel-dineval: 9 hours
travel-konig: 11 hours
travel-dougan: 8.5 hours
travel-easthaven: 0 hours
travel-good: 4.5 hours
travel-lonelywood: 15.5 hours
travel-targos: 9.5 hours
travel-termalaine: 13.5 hours
tags: town, location
---

## Information
> [!infobox] +
> # Easthaven
> ![[Easthaven Logo.png| cover hsmall]]
> ##### Notable Characters
> | Name | Status |
> | ---- | ---- |
> | **Speaker Danneth** | Alive |
> | **Captain Imdra** | Alive |
> ##### Travel Time 🕤
> | Category | Walking | Current |
> | :----: | :----: | :----: |
> | **Bremen** | ` =this.travel-bremen`  | ` =this.travel-bremen * [[Map of The North]].travel-current`  |
> | **Bryn Shander** | ` =this.travel-bryn` | ` =this.travel-bryn * [[Map of The North]].travel-current` |
> | **Caer-Dineval** | ` =this.travel-dineval`  | ` =this.travel-dineval * [[Map of The North]].travel-current`  |
> | **Caer-Konig** | ` =this.travel-konig`  | ` =this.travel-konig * [[Map of The North]].travel-current`  |
> | **Dougan's Hole** | ` =this.travel-dougan`  | ` =this.travel-dougan * [[Map of The North]].travel-current`  |
> | **Easthaven** | ` =this.travel-easthaven`  | ` =this.travel-easthaven * [[Map of The North]].travel-current`  |
> | **Good Mead** | ` =this.travel-good`  | ` =this.travel-good * [[Map of The North]].travel-current`  |
> | **Lonelywood** | ` =this.travel-lonelywood`  | ` =this.travel-lonelywood * [[Map of The North]].travel-current`  |
> | **Targos** | ` =this.travel-targos`  | ` =this.travel-targos * [[Map of The North]].travel-current`  |
> | **Termalaine** | ` =this.travel-termalaine`  | ` =this.travel-termalaine * [[Map of The North]].travel-current`  |

> *Walking into Easthaven is like stepping into Icewind Dale’s past—the place is a living example of the boomtown way of life that gripped all of Ten-Towns centuries ago. In the generations since, as other towns have settled into a predictable pattern of existence, Easthaven has continued to grow and reinvent itself. After the Eastway was paved, Easthaven evolved into a frontier traders’ paradise, fueling the jealousy of its neighbors.*
> *Easthaven’s founders were thieves from the Duchy of Cape Velen, on a peninsula far to the south. They refused to kowtow to a powerful thieves’ guild and were driven out. To this day, Easthaven honors its shady founders by declaring pickpocketing legal within the town limits—which explains the “Watch thy pouch!” signs posted in various local establishments.*

Arriving here, Jaeger is [[Making it to Easthaven|pickpocketed]] before even reaching the Inn. The rumors of murders circulate the town, and at some point during the night [[Dzaan]] is captured by Easthaven authorities. The party awakes to the cheers of the crowd as he is set ablaze in an [[The Execution|execution]] by pyre. The party interferes by trying (and failing) to save him. As recompense, they are tasked by [[Danneth]] and [[Imdra]] with finding missing fishermen who went out onto the water drunk and never came back.

The Duergar note found in the bunker leads to the Ferry. Investigation proves fruitful as three enemies are captured, brought back to town, and [[Team Interrogation|interrogated]].

The Chardalyn Dragon attacked this town, but the party was able to defeat the construct before it could completely destroy the town. Also, due to [[Niles]] warning Imdra of a possible imminent attack, they were able to defend themselves to some extent. Half the town was destroyed, but some of the civilians were able to escape.

### Locations and Locals

###### Easthaven Town Hall
```dataview
LIST status
FROM #npc
WHERE current-location = "Easthaven Town Hall"
SORT file.name ASC
```
----

###### White Lady Inn
```dataview
LIST status
FROM #npc
WHERE current-location = "White Lady Inn"
SORT file.name ASC
```
----

###### Wet Trout Tavern
```dataview
LIST status
FROM #npc
WHERE current-location = "Wet Trout Tavern"
SORT file.name ASC
```
----

###### Unknown
```dataview
LIST status
FROM #npc
WHERE current-town = "Easthaven" AND current-location = BLANK
SORT file.name ASC
```

## Quests

```dataview
LIST status
FROM #quest
WHERE contains(town,"Easthaven")
SORT session DESC
```

## Sessions

```dataview
LIST session
FROM #summary
WHERE contains(location, "Easthaven")
SORT session DESC
```


## Items Remaining
```dataview
LIST
FROM #item
WHERE icontains(item-town,"Easthaven")
SORT file.name ASC
```

## Map
[[Easthaven Map.jpg|View this Image]]

[[Map of The North|↩️ Return to Map]]