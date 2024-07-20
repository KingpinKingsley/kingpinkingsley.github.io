---
affiliation: Ryker
current-town: 
current-location: 
status: Alive
tags:
  - character
  - npc
---

## Information
> [!infobox] +
> # Connor
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | - |
> | **Affiliation** | [[Ryker]] |

The alleged bodyguard of the Broomson family.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Connor")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Connor")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]