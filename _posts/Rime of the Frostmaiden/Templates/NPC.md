---
affiliation:
current-town: 
current-location: 
status:
tags: character, npc
---

## Information
> [!infobox] +
> # {{title}}
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | {Status} |
> | **Race** | {Race} |
> | **Affiliation** | {Affiliation} |

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "{{title}}")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "{{title}}")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]