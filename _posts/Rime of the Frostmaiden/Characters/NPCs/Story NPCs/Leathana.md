---
affiliation:
current-town: Easthaven
current-location: 
status: Deceased
tags: character, npc
---

## Information
> [!infobox] +
> # Leathana
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Deceased |
> | **Race** | Ghost |
> | **Affiliation** | - |

Ghost of the young woman who went missing on the lake near [[Easthaven]]. She is the apparition called during the [[Easthaven#**White Lady Inn**|White Lady Inn]] séance that tells of her husband, [[Todd]], who cheated on her.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Leathana")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Leathana")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]