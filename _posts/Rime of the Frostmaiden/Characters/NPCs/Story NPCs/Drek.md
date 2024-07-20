---
affiliation: Grandolpha's Faction
current-town: 
current-location: Sunblight Stronghold 
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Drek
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Duergar |
> | **Affiliation** | [[Grandolpha]] |

A random Duergar that serves Grandolpha. Met within [[Sunblight Stronghold]].

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Drek")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Drek")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]