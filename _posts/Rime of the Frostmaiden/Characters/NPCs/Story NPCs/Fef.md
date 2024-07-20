---
affiliation:
current-town: Good Mead
current-location: Mead Hall
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Fef
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | - |
> | **Affiliation** | [[Good Mead]] |

Trapper/Hunter that sold [[Joyelle]] the [[Fox]] for 15 gold. He also gave more insight into the rumor surrounding people seeing lights and dying when they go to investigate.

## Quest

```dataview
LIST status
FROM #quest 
WHERE contains(npc, "Fef")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE contains(npc, "Fef")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]