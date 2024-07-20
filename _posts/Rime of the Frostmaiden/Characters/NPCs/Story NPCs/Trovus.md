---
affiliation:
current-town: Caer-Konig
current-location: Northern Lights Inn 
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Trovus
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Dragon-Born |
> | **Affiliation** | Caer-Konig Authorities |

The drunkard and near-useless speaker who tasks the party with finding and apprehending the bandits ransacking the [[Caer-Konig|town]]. His quest of finding the bandits is concluded after the party returns with the location of missing items from the town. Trovus offers no reward to the party, so [[Allie]] and [[Cori]] come up with compensation.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Trovus")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Trovus")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]