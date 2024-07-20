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
> # Tali
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Half-Elf |
> | **Affiliation** | - |

A student come to the north to study the creature in the lake. Requests [[Niles]] to only defeat the creature and not kill it, so that she can later study it. She warned Niles of the creature before the ranger went out onto the lake at the behest of [[Berylbore]].

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Tali")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Tali")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]