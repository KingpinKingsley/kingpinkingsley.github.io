---
locations: Eastside Inn, Blue Clam Tavern
alias: Eastside Inn, Blue Clam Tavern
travel-bremen: 7 hours
travel-bryn: 6 hours
travel-dineval: 16.5 hours
travel-konig: 18.5 hours
travel-dougan: 16 hours
travel-easthaven: 13.5 hours
travel-good: 12 hours
travel-lonelywood: 2 hours
travel-targos: 4 hours
travel-termalaine: 0 hours
tags: town, location
---

## Information
> [!infobox] +
> # Termalaine
> ![[Termalaine Logo.png| cover hsmall]]
> ##### Notable Characters
> | Name | Status |
> | ---- | ---- |
> | **Speaker** | - |
> | **Sheriff** | - |
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

> *Founded by Calishite settlers who appreciated beauty, Termalaine is widely regarded as the most picturesque town in Icewind Dale, spreading out from the shore of Maer Dualdon and bordered on the north and west by tall pines. Its buildings incorporate carvings of wizards, homunculi, tigers, and smiling djinn.*

Has been known as a mining town.


### Locations and Locals

###### Eastside Inn
```dataview
LIST status
FROM #npc
WHERE current-location = "Eastside Inn"
SORT session DESC
```

###### Blue Clam Tavern
```dataview
LIST status
FROM #npc
WHERE current-location = "Blue Clam Tavern"
SORT session DESC
```

## Quests

```dataview
LIST status
FROM #quest
WHERE contains(town,"Termalaine")
SORT session DESC
```

## Sessions

```dataview
LIST session
FROM #summary
WHERE contains(location, "Termalaine")
SORT session DESC
```

## Map
[[Termalaine Map.jpg|View this Image]]

[[Map of The North|↩️ Return to Map]]