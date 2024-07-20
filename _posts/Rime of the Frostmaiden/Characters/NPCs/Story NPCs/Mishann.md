---
affiliation:
current-town: Bryn Shander
current-location: Church of the Sun God
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Mischann
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | - |
> | **Affiliation** | [[Bryn Shander#Church of the Sun God\|Church of the Sun God]] |

A follower and priestess of the Sun God who greats the party when they first visit the church. She actively disagrees with the sacrifices being made to Auril, and the membership of her church is dwindling.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Mishann")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Mishann")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]