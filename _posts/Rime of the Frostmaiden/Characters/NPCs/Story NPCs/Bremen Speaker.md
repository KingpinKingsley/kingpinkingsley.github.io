---
affiliation: Bremen
current-town: Bremen
current-location: 
status: Alive
tags:
  - character
  - npc
---

## Information
> [!infobox] +
> # Bremen Speaker
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive|
> | **Race** | Dwarf |
> | **Affiliation** | [[Bremen]] |

The ancient, dwarven Speaker of [[Bremen]] who continually wanders off outside of town. [[Jared]], the town clerk, told [[Niles]] about this recurring instance. He was not met when the party passed through Bremen on the way to meet with Angajuk the whale and fetch the Codicil of White for Vellynne.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Bremen Speaker")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Bremen Speaker")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]