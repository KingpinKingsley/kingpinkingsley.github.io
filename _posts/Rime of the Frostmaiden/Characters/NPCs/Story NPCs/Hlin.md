---
affiliation:
current-town: Bryn Shander
current-location: Bryn Shander Town Square
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Hlin
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Dwarf |
> | **Affiliation** | - |

A retired adventurer who tasked the party with finding the murderer travelling between the Ten Towns. One of the victims was someone very close with, and so she spent every day in the markets trying to get help in her mission. Her quest was concluded when the party killed and revealed that the culprit was [[Sephek]].

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Hlin")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Hlin")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]