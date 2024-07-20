---
affiliation: Hruna's Crew
current-town: Bryn Shander
current-location: Northlook Inn & Tavern
status: Alive
tags: character, npc
---

## Information
> [!infobox] +
> # Hruna
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Alive |
> | **Race** | Dwarf |
> | **Affiliation** | Hruna's Crew |

The leader of a squad of dwarven merchants transporting wares between the Dwarven Valley and Bryn Shander. She tasks the party with finding her missing crewmate and recovering wares. This quest was concluded when the party brought back proof of her crewmate's death, along with a cart of wares. [[Storn]] and [[Korux]] are her remaining crew as [[Oobok]] is the one who died.

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Hruna")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Hruna")
SORT session DESC
```