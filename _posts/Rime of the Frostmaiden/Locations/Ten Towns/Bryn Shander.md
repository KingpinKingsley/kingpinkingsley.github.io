---
locations: Church of the Sun God, Bryn Shander Town Hall, Bryn Shander Town Square, Northlook Inn & Tavern
aliases:
  - Church of the Sun God
  - Bryn Shander Town Hall
  - Northlook Inn & Tavern
  - Bryn Shander Town Square
travel-bremen: 5 hours
travel-bryn: 0 hours
travel-dineval: 10.5 hours
travel-konig: 12.5 hours
travel-dougan: 10 hours
travel-easthaven: 7.5 hours
travel-good: 6 hours
travel-lonelywood: 8 hours
travel-targos: 2 hours
travel-termalaine: 6 hours
tags:
  - town
  - location
---

## Information
> [!infobox] +
> # Bryn Shander
> ![[Bryn Shander Logo.png| cover hsmall]]
> ##### Notable Characters
> | Name | Status |
> | ---- | ---- |
> | **Speaker [[Duvessa]]** | Alive |
> | **Sheriff [[Markham]]** | Alive |
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

> *The first stop for most visitors to Icewind Dale is Bryn Shander, a walled town perched atop a cold, lonely, wind-lashed hill. Bright lanterns suspended over narrow streets twist in the wind and add flecks of color to the town’s otherwise drab surroundings.*
> *The friendliness in this settlement has dwindled of late. Auril’s unyielding winter has greatly reduced the number of visitors to Bryn Shander, and local trade is suffering for it, eating away at the locals’ sense of humor and goodwill. Still, there is no safer place in Icewind Dale to spend coin or spend the night.*
> *The walls of the town stand some 30 feet high and are defined by two concentric rings of upright wooden poles, the gap between them filled with dirt and rubble. The outer ring of poles rises above the top of the wall, providing a rampart for defenders stationed on the wood-planked walkway. The wall’s hinged gates are 15 feet tall and can be barred from the inside with iron-banded wood beams. These gates are closed when it’s dark outside—which is to say more often than not.*

Murder mystery is solved while finding the wares of the missing dwarves.


### Locations and Locals

**Population:** 1,200

###### Bryn Shander Town Hall
```dataview
LIST status
FROM #npc
WHERE contains(current-location, "Bryn Shander Town Hall")
SORT session DESC
```
---

###### Church of the Sun God
A gathering place for the worshipers of Amaunator, a "god of the sun known to take both male and female forms".
```dataview
LIST status
FROM #npc
WHERE current-location = "Church of the Sun God"
SORT session DESC
```
---

###### Northlook Inn & Tavern
Both and inn and tavern, this location is frequented by adventurers. It's also the cheapest of the two inns in town.
```dataview
LIST status
FROM #npc
WHERE current-location = "Northlook Inn & Tavern"
SORT session DESC
```
---

###### Bryn Shander Town Square
```dataview
LIST status
FROM #npc
WHERE current-location = "Bryn Shander Town Square"
SORT session DESC
```
---

###### Unknown
```dataview
LIST status
FROM #npc
WHERE current-town = "Bryn Shander" AND current-location = BLANK
SORT file.name ASC
```


## Quests

```dataview
LIST status
FROM #quest
WHERE contains(town, "Bryn Shander")
SORT session DESC
```

**Rewards:** 
Black Iron discount from Hruna. 25 gold each from Hlin.

## Sessions

```dataview
LIST session
FROM #summary
WHERE contains(location, "Bryn Shander")
SORT session DESC
```


## Map
[[Bryn Shander Map.jpg|View this Image]]

[[Map of The North|↩️ Return to Map]]