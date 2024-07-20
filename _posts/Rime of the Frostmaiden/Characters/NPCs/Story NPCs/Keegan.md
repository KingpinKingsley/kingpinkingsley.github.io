---
affiliation:
current-town: Targos
current-location: Keegan's Home
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Keegan
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | - |
> | **Affiliation** | - |

Husband to [[Garret]], and the one who tasks the party with making a trip to [[Kelvin's Cairn]] to perform a rescue. His quest is successfully concluded when the party [[Targos|returns]] with his partner. He rewards the group with scrimshaw artwork he makes along with helping the group get a discount with the local inn.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Keegan")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Keegan")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]