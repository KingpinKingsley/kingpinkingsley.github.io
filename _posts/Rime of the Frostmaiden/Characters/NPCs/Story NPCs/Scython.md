---
affiliation:
current-town: Easthaven
current-location: Wet Trout Tavern
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Scython
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Tiefling |
> | **Affiliation** | - |

A boisterous man that tagged along with the party to speak with the authorities of possible trespassers on the [[The Ferry Hideout|Ferry]] near [[Easthaven]]. He does not seem to be popular in town.

He owns the ferry.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Scython")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Scython")
SORT session DESC
```