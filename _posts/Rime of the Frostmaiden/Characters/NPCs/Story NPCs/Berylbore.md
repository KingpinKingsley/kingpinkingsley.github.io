---
affiliation: 
current-town: Bremen
current-location: 
status: Alive
tags:
  - character
  - npc
---

## Information
> [!infobox] +
> # Grynsk Berylbore
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Dwarf |
> | **Affiliation** | - |

Old man who ushered Niles to go out onto the lake to find fish. Every fish Niles caught would be rewarded. He also neglected to tell Niles of the creature living beneath the waters of the lake. [[Tali]] seems to know him.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Berylbore")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Berylbore")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]