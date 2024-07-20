---
affiliation: 
current-town: 
current-location: 
status: Alive
tags:
  - character
  - npc
---

## Information
> [!infobox] +
> # Mylbor
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | - |
> | **Affiliation** | - |

A warrior out to hunt the scarlet yeti. He mentioned this creature to the party while still in Bryn Shander, and would soon depart for the area around Caer-Konig.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Mylbor")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Mylbor")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]