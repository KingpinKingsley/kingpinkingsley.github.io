---
affiliation: Auril
current-town: 
current-location: 
status: Alive
tags:
  - character
  - npc
---

## Information
> [!infobox] +
> # Auril
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Deity |
> | **Affiliation** | Auril |

Appears as a massive owl riding another bird.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Auril")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Auril")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]