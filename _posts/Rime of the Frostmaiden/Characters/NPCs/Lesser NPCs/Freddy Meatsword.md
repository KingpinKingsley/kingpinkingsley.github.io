---
affiliation: 
current-town: 
current-location: 
status: Deceased
tags:
  - character
  - npc
---

## Information
> [!infobox] +
> # Freddy Meatsword
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | {Status} |
> | **Race** | {Race} |
> | **Affiliation** | {Affiliation} |

The unfortunate soul chosen for the lottery. The party doesn't know of this person.


NPC created by Candor.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Freddy Meatsword")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Freddy Meatsword")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]