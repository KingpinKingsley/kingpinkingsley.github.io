---
locations: Northern Lights Inn, Frozenfar Expeditions, Trovus' Home
alias: Northern Lights Inn, Frozenfar Expeditions, Trovus' Home
travel-bremen: 17.5 hours
travel-bryn: 12.5 hours
travel-dineval: 2 hours
travel-konig: 0 hours
travel-dougan: 14 hours
travel-easthaven: 11 hours
travel-good: 10 hours
travel-lonelywood: 20.5 hours
travel-targos: 14.5 hours
travel-termalaine: 18.5 hours
tags: town, location
---

## Information
> [!infobox] +
> # Caer-Konig
> ![[Caer-Konig Logo.png| cover hsmall]]
> ##### Notable Characters
> | Name | Status |
> | ---- | ---- |
> | **Speaker Trovus** | Alive |
> ##### Travel Time 🕤
> | Category | Walking | Current |
> | :----: | :----: | :----: |
> | **Bremen** | ` =this.travel-bremen`  | ` =this.travel-bremen * [[Map of The North]].travel-mount`  |
> | **Bryn Shander** | ` =this.travel-bryn` | ` =this.travel-bryn * [[Map of The North]].travel-mount` |
> | **Caer-Dineval** | ` =this.travel-dineval`  | ` =this.travel-dineval * [[Map of The North]].travel-mount`  |
> | **Caer-Konig** | ` =this.travel-konig`  | ` =this.travel-konig * [[Map of The North]].travel-mount`  |
> | **Dougan's Hole** | ` =this.travel-dougan`  | ` =this.travel-dougan * [[Map of The North]].travel-mount`  |
> | **Easthaven** | ` =this.travel-easthaven`  | ` =this.travel-easthaven * [[Map of The North]].travel-mount`  |
> | **Good Mead** | ` =this.travel-good`  | ` =this.travel-good * [[Map of The North]].travel-mount`  |
> | **Lonelywood** | ` =this.travel-lonelywood`  | ` =this.travel-lonelywood * [[Map of The North]].travel-mount`  |
> | **Targos** | ` =this.travel-targos`  | ` =this.travel-targos * [[Map of The North]].travel-mount`  |
> | **Termalaine** | ` =this.travel-termalaine`  | ` =this.travel-termalaine * [[Map of The North]].travel-mount`  |

> *The white, snow-covered slopes of Kelvin’s Cairn loom large behind this quiet lakeside town. Caer-Konig started as a camp for a group of mountaineers from the northern Moonsea region. As the camp grew, a wooden palisade was added to discourage raiders. Later came the stone castle of Caer-Konig. Alas, neither the palisade nor the castle fared well; both fell to orcs before falling into ruin.*
*Caer-Konig as it is known today consists of terraced rows of houses that recede from the shore of Lac Dinneshere like the tiers of an amphitheater. The harbor is frozen, its docks skewed and broken by the shifting ice. Buried under the snow on the slopes above the last row of houses are the ruins of the Caer that gave the town its name—a reminder to the people of Caer-Konig that nothing lasts in this corner of the world.*

Thanks to the efforts of the party, the local inn has their keepsake lantern again. As a reward, all stays at the Northern Lights Inn are free.

Mori and Jaeger are known as wealthy business partners.

### Locations and Locals

###### Northern Lights Inn
```dataview
LIST status
FROM #npc
WHERE contains(current-location, "Northern Lights Inn")
SORT session DESC
```
----

###### Frozenfar Expeditions
```dataview
LIST status
FROM #npc
WHERE contains(current-location, "Frozenfar Expeditions")
SORT session DESC
```

----

###### Trovus' Home
```dataview
LIST status
FROM #npc
WHERE contains(current-location, "Trovus' Home")
SORT session DESC
```

## Quests

```dataview
LIST status
FROM #quest
WHERE contains(town, "Caer-Konig")
SORT session DESC
```

**Rewards:**

## Sessions

```dataview
LIST session
FROM #summary
WHERE contains(location, "Caer-Konig")
SORT session DESC
```

## Map
[[Caer-Konig Map.jpg|View this Image]]

[[Map of The North|↩️ Return to Map]]