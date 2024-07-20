---
affiliation: Candor
current-town: 
current-location: 
status:
tags: character, npc
---

## Information
> [!infobox] +
> # Candor's Mom
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | {Status} |
> | **Race** | {Race} |
> | **Affiliation** | {Affiliation} |

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Candor's Mom")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Candor's Mom")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]