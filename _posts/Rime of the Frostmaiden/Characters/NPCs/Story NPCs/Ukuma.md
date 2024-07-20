---
affiliation: 
current-town: 
current-location: Isle of Solstice
status: Alive
tags:
  - character
  - npc
---

## Information
> [!infobox] +
> # Ukuma
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Awakened Walrus |
> | **Affiliation** | - |

An awakened walrus given the duty of guarding the four trials within the [[Isle of Solstice]]. He doesn't seem to care too much about his job, instead opting to chat with the party and ask for "snackums" whenever he can.

He explains the nature of the trials to the party.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Ukuma")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Ukuma")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]