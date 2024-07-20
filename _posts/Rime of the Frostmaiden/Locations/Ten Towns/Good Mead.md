---
locations: Mead Hall
alias: Mead Hall
travel-bremen: 11 hours
travel-bryn: 6 hours
travel-dineval: 8 hours
travel-konig: 10 hours
travel-dougan: 4 hours
travel-easthaven: 4.5 hours
travel-good: 0 hours
travel-lonelywood: 14 hours
travel-targos: 8 hours
travel-termalaine: 12 hours
tags: town, location
---

## Information
> [!infobox] +
> # Good Mead
> ![[Good Mead Logo.png| cover hsmall]]
> ##### Notable Characters
> | Name | Status |
> | ---- | ---- |
> | **Speaker** | Deceased |
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

> *Founded by immigrants from Chult and the Vilhon Reach, Good Mead is nestled between Redwaters and a nearby evergreen forest. The town’s squat dwellings, adorned with carvings of dinosaurs and serpents, are overshadowed by the two-story structure of the mead hall, its eaves carved and painted to resemble wyverns. As honey is the key ingredient in mead, the town literally buzzes with the droning of bees.*

The Speaker having recently been killed an an upcoming election to replace them is the talk of the town. A talking [[Fox]] is was advertised and sold, and information concerning rumors was gained. The party takes it onto themselves to investigate the giants that killed the Speaker and several others when they tried to track down and get back their stolen mead. Eventually, the giants are all killed, and the town is eager regain their stolen wares.

Good Mead was destroyed by the Chardalyn Dragon. It is implied that some citizens were able to escape, but the town is gone.

### Locations and Locals

###### Mead Hall
```dataview
LIST status
FROM #npc
WHERE current-location = "Mead Hall"
SORT file.name ASC
```

## Quests

```dataview
LIST status
FROM #quest
WHERE contains(town,"Good Mead")
SORT session DESC
```

## Sessions

```dataview
LIST session
FROM #summary
WHERE contains(location, "Good Mead")
SORT session DESC
```

## Map
[[Good Mead Map.jpg|View this Image]]

[[Map of The North|↩️ Return to Map]]