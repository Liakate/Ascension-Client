# C_LootLockout



**Members:** 10  •  **Functions:** 10  •  **Interface calls:** 5 (across up to 2 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetEncounterData | function | C_LootLockout.GetEncounterData(...) |  |
| GetEncounterDatasForMapAndDifficulty | function | C_LootLockout.GetEncounterDatasForMapAndDifficulty(...) |  |
| GetLootLockoutTimeRemaining | function | C_LootLockout.GetLootLockoutTimeRemaining(...) |  |
| GetLootLockouts | function | C_LootLockout.GetLootLockouts(...) |  |
| GetUnitEncounterID | function | C_LootLockout.GetUnitEncounterID(...) |  |
| GetUnitLootLockForEncounter | function | C_LootLockout.GetUnitLootLockForEncounter(...) |  |
| HasEncounterDatasForMapAndDifficulty | function | C_LootLockout.HasEncounterDatasForMapAndDifficulty(...) |  |
| ListInstanceBinds | function | C_LootLockout.ListInstanceBinds(arg1, arg2) | for _, mapID in ipairs(C_LootLockout.ListInstanceBinds(isRaid == 1, difficultyID)) do |
| QueryInstanceBinds | function | C_LootLockout.QueryInstanceBinds() |  |
| ResetInstanceDifficulty | function | C_LootLockout.ResetInstanceDifficulty(arg1) |  |



## Notes


- 7 member(s) had a runtime probe marked `ok` in the scan data.
