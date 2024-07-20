---
affiliation:
current-town: 
current-location: Unknown Hero's Tomb
status: Deceased
tags: character, npc
---

## Information
> [!infobox] +
> # Unknown Hero
> ##### Character
> | Category | Information |
> | ---- | ---- |
> | **Type** | Non-Player Character |
> | **Status** | Deceased |
> | **Race** | - |
> | **Affiliation** | - |

A hero who died thousands of years before who has their story told by pictograms on the walls of their [[Unknown Hero's Tomb|tomb]] within the [[Duhg's Cave|cave]] near [[Good Mead]]. While their identity is lost to time, it is assumed they died due to the stacking curses of the items they are wearing within their sarcophagus ([[Augur's Dagger|Dagger]], [[Pearl of Power|Pearl Necklace]], and [[Wand of the War Mage|Wand]]). The party returns the dagger to its sheath within this hero's grasp, ending the curse on [[Candor]].

## Quest

```dataview
LIST status
FROM #quest 
WHERE icontains(npc, "Unknown Hero")
SORT session DESC
```

## Appears In...
```dataview
LIST session
FROM #summary
WHERE icontains(npc, "Unknown Hero")
SORT session DESC
```

[[List of NPCs|↩️ Return to NPC List]]