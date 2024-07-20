---
nearest-town: Dougan's Hole
npc: Dredavex, Vorryn, Rin, Rix, Zglarrd
tags: location
---

## Information
> [!infobox] +
> # Dredavex's Ship
> ##### Remaining Characters
> | Name | Status |
> | ---- | ---- |
> | **[[Dredavex]]** | Alive |
> | **[[Vorryn]]** | Alive |
> | **[[Rin]]** | Alive |
> | **[[Rix]]** | Alive |
> | **[[Zglarrd]]** | Alive |
> | **The Amalgamation** | Alive |
> | **Alien Pets** | Alive |
> ##### Location
> | Catagory | Information |
> | ---- | ---- |
> | **Encounters** | The Amalgamation |

A nautical-looking, shelled airship that crashed, stranding its inhabitants west of Sunblight Stronghold. The ship is currently without power and in need of [[Psi Crystal|Psi Crystals]], or else the creatures inside will freeze to death.

Upon first arrival, the party is attacked by the Amalgamation: a creature consisting of several entities (men, animals, etc.) combined into one chimeric form.

An [[Alien Rifle|alien rifle]] and its corresponding ammunition are within a crate.

While racing back to the towns to hunt and destroy the chardalyn dragon, the party passes by the place where the ship once stood. There is now a crater. Dredavex detonated the ship to save their family from suffering, killing everyone inside. There are footsteps nearby indicating that Mori was able to leave prior to the explosion.


## Affiliated Quests
```dataview
LIST status
FROM #quest
WHERE contains(location, "Dredavex's Ship")
SORT session DESC
```

## Sessions Visited
```dataview
LIST session
FROM #summary
WHERE icontains(location, "Dredavex's Ship")
SORT session DESC
```

## Items Remaining
```dataview
LIST
FROM #item
WHERE icontains(item-location,"Dredavex's Ship")
SORT file.name ASC
```

[[Map of The North|↩️ Return to Map]]