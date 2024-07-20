---
affiliation:
current-town: 
current-location: 
status: Alive
tags: character, npc, lesser
---

## Information
> [!infobox] +
> # Darryl
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | - |
> | **Affiliation** | Darryl's Caravan |

Owner of the Caravan that brought the party to [[Bryn Shander]].

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Darryl")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Darryl")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]