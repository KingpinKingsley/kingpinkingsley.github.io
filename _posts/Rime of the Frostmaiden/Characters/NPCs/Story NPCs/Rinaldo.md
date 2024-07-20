---
affiliation:
current-town: Easthaven
current-location: White Lady Inn
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Rinaldo
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | - |
> | **Affiliation** | -|

The organizer of the [[Easthaven#**White Lady Inn**|White Lady Inn]] séance. He was possessed by the ghost, [[Leathana]], for the duration of the time. He is considered persuasive since he convinced several party members to attend.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Rinaldo")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Rinaldo")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]