---
affiliation: Candor
current-town: 
current-location: 
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Bubbles
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive|
> | **Race** | Dog |
> | **Affiliation** | - |

The sled dog [[Candor]] adopted.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Bubbles")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Bubbles")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]