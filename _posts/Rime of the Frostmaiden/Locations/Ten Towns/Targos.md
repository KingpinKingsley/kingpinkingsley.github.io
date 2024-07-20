---
locations: Keegan's Home
alias: Keegan's Home
travel-bremen: 3 hours
travel-bryn: 2 hours
travel-dineval: 12.5 hours
travel-konig: 14.5 hours
travel-dougan: 12 hours
travel-easthaven: 9.5 hours
travel-good: 8 hours
travel-lonelywood: 6 hours
travel-targos: 0 hours
travel-termalaine: 4 hours
tags: town, location
---

## Information
> [!infobox] +
> # Targos
> ![[Targos Logo.png| cover hsmall]]
> ##### Notable Characters
> | Name | Status |
> | ---- | ---- |
> | **Speaker** | Unknown |
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

> *Like Bryn Shander, Targos is encircled by a wooden wall, which helps to protect the town against orcs and other threats from the wilderness. The wall extends out into the lake, creating a safe harbor for the town’s boats. But now Auril’s long winter has frozen the water in the harbor, and many of Targos’s boats are trapped in the ice. Fishers must drag their smaller vessels across the ice to get to the unfrozen lake beyond the harbor walls.*

### Locations and Locals

###### Keegan's Home
```dataview
LIST status
FROM #npc
WHERE contains(current-location,"Keegan's Home")
SORT session DESC
```


## Quests

```dataview
LIST status
FROM #quest
WHERE contains(town,"Targos")
SORT session DESC
```

## Sessions

```dataview
LIST session
FROM #summary
WHERE contains(location, "Targos")
SORT session DESC
```

## Map
[[Targos Map.jpg|View this Image]]

[[Map of The North|↩️ Return to Map]]