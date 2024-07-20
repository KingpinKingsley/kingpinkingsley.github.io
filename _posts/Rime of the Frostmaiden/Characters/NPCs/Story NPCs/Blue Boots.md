---
affiliation:
current-town: 
current-location: Kelvin's Cairn
status: Deceased
tags: character, npc
---

## Information
> [!infobox] +
> # Blue Boots
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Deceased |
> | **Race** | - |
> | **Affiliation** | - |

A long-dead adventurer who's final resting place is near [[Astrix|Astrix's]] near the peak of [[Kelvin's Cairn]]. No one knows his real name.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Blue Boots")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Blue Boots")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]