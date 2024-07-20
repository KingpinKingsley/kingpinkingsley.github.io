
--- start-multi-column: Quest_Terms
```column-settings
Number of Columns: 2
Shadow: false
Border: false
Largest Column: standard
```


#### Status

- **Abandoned** = Information is known about the quest, but not investigated.
- **Ignored** = No information known, not investigated.
- **In-Progress** = Actively being pursued by party.
- **Not Started** = Information known, but no actions have been taken yet.
- **Completed** = All requirements have been fulfilled.

--- column-end ---



#### Type

- **Unconfirmed Rumor** = Information has been overheard. Nothing has been learned to confirm this this rumor.
- **Confirmed Rumor** = Information has been overheard *and* confirmed by another source. Actionable rumor.
- **Active Quest** = This is a task that can be completed.

--- end-multi-column

#### Quest List
```dataview
TABLE status AS Status, quest-type AS Type, danger AS Danger
FROM "Quests"
SORT status ASC
```
