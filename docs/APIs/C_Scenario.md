# C_Scenario



**Members:** 5  •  **Functions:** 5  •  **Interface calls:** 5 (across up to 1 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetActiveStage | function | C_Scenario.GetActiveStage() | local stageNumber, stageName = C_Scenario.GetActiveStage() |
| GetEncounterAtIndex | function | C_Scenario.GetEncounterAtIndex(arg1) | local encounterInfo = C_Scenario.GetEncounterAtIndex(i) |
| GetNumEncounters | function | C_Scenario.GetNumEncounters() | for i = 1, C_Scenario.GetNumEncounters() do |
| GetScenarioName | function | C_Scenario.GetScenarioName(...) |  |
| IsInScenario | function | C_Scenario.IsInScenario() | if not C_Scenario.IsInScenario() then |



## Notes


- 1 member(s) had a runtime probe marked `ok` in the scan data.
