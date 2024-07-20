---
locations: Castle Dineval, Uphill Climb Tavern
alias: Castle Dineval, Uphill Climb Tavern
travel-bremen: 15.5 hours
travel-bryn: 10.5 hours
travel-dineval: 0 hours
travel-konig: 2 hours
travel-dougan: 12 hours
travel-easthaven: 9 hours
travel-good: 8 hours
travel-lonelywood: 18.5 hours
travel-targos: 12.5 hours
travel-termalaine: 16.5 hours
tags: town, location
---

## Information
> [!infobox] +
> # Caer-Dineval
> ![[Caer-Dineval Logo.png| cover hsmall]]
> ##### Notable Characters
> | Name | Status |
> | ---- | ---- |
> | **Speaker Crannoc** | Alive |
> | **Avarice** | Alive |
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

> *In generations past, travelers to Caer-Dineval had to follow the rocky shore of Lac Dinneshere until after several hours they spied a small fortress (the “caer” for which the town is named) jutting up from the prominence where it overlooks the lake. A ferry out of Easthaven made the arduous trek unnecessary for merchants and other travelers, but the ferry was discontinued two months ago, cutting off Caer-Dineval (and its eastward neighbor, Caer-Konig) from the rest of Ten-Towns except by the overland route. Town residents are furious that the ferry service has stopped, mainly because they have not received deliveries of mead from the town of Good Mead, and the taverns have run dry.*
> *As if things weren’t bad enough, the town’s harbor has frozen over, and the town’s speaker, Crannoc Siever, has taken to his bed and is apparently too sick to make public appearances or press the Council of Speakers to get the ferry from Easthaven running again.*

Avarice and her men have overtaken the town, having imprisoned the Speaker within the Castle. The party will receive accommodations whenever they stay in this town. 

The Chardalyn Dragon attacked this town, but the party was able to defeat the construct before it could do substantial damage or fly away.

### Locations and Locals

###### Castle Dineval
```dataview
LIST status
FROM #npc
WHERE current-location = "Castle Dineval"
SORT file.name ASC
```
-----

###### Uphill Climb Tavern 
The tavern where the party learns rumors of Castle Dineval and the Speaker of the town.
```dataview
LIST status
FROM #npc
WHERE current-location = "Uphill Climb Tavern"
SORT file.name ASC
```

----

###### Unknown
```dataview
LIST status
FROM #npc
WHERE current-town = "Caer-Dineval" AND current-location = BLANK
SORT file.name ASC
```

## Quests

```dataview
LIST status
FROM #quest
WHERE contains(town, "Caer-Dineval")
```

## Sessions

```dataview
LIST session
FROM #summary
WHERE contains(location, "Caer-Dineval")
SORT session DESC
```


## Map
[[Caer-Dineval Map.jpg|View this Image]]

[[Map of The North|↩️ Return to Map]]