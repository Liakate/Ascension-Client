# C_MythicPlus



**Members:** 12  •  **Functions:** 12  •  **Interface calls:** 34 (across up to 5 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ActivateKeystone | function | C_MythicPlus.ActivateKeystone() |  |
| GetActiveKeystoneChampions | function | C_MythicPlus.GetActiveKeystoneChampions() | local champions = C_MythicPlus.GetActiveKeystoneChampions() |
| GetActiveKeystoneEncounters | function | C_MythicPlus.GetActiveKeystoneEncounters() | local encountersInfo = C_MythicPlus.GetActiveKeystoneEncounters() |
| GetActiveKeystoneInfo | function | C_MythicPlus.GetActiveKeystoneInfo() | local activeKeystone = C_MythicPlus.GetActiveKeystoneInfo() |
| GetActiveKeystoneTime | function | C_MythicPlus.GetActiveKeystoneTime() | local timeLeft, timeLimit = C_MythicPlus.GetActiveKeystoneTime() |
| GetActiveKeystoneTrash | function | C_MythicPlus.GetActiveKeystoneTrash() | local trash = C_MythicPlus.GetActiveKeystoneTrash() |
| GetCurrentAffixes | function | C_MythicPlus.GetCurrentAffixes() | local affixes = C_MythicPlus.GetCurrentAffixes() |
| GetKeystoneInfo | function | C_MythicPlus.GetKeystoneInfo(arg1) | local keystoneInfo = C_MythicPlus.GetKeystoneInfo(keystoneID) |
| GetMapEncounters | function | C_MythicPlus.GetMapEncounters(arg1) | self:UpdateEncounters(C_MythicPlus.GetMapEncounters(dungeonID)) |
| GetMapFinalEncounter | function | C_MythicPlus.GetMapFinalEncounter(arg1) | self.finalEncounter = C_MythicPlus.GetMapFinalEncounter(dungeonID) |
| IsItemKeystone | function | C_MythicPlus.IsItemKeystone(arg1) | if itemID and C_MythicPlus.IsItemKeystone(itemID) then |
| IsKeystoneActive | function | C_MythicPlus.IsKeystoneActive() | if C_MythicPlus.IsKeystoneActive() then |
