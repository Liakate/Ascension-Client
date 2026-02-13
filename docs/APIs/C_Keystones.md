# C_Keystones



**Members:** 16  •  **Functions:** 16  •  **Interface calls:** 37 (across up to 3 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_Keystones.lua` line 72




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ASCENSION_MYTHIC_PLUS_KEYSTONE_ACTIVATION_WINDOW_VISIBILITY_CHANGED | function | C_Keystones:ASCENSION_MYTHIC_PLUS_KEYSTONE_ACTIVATION_WINDOW_VISIBILITY_CHANGED() | function C_Keystones:ASCENSION_MYTHIC_PLUS_KEYSTONE_ACTIVATION_WINDOW_VISIBILITY_CHANGED() |
| GetCurrentSetBest | function | C_Keystones.GetCurrentSetBest() | local bestKey = C_Keystones.GetCurrentSetBest() |
| GetCurrentSetString | function | C_Keystones.GetCurrentSetString() | function C_Keystones.GetCurrentSetString() |
| GetDungeonBest | function | C_Keystones.GetDungeonBest(arg1) | function C_Keystones.GetDungeonBest(dungeonID) |
| GetDungeonBestLink | function | C_Keystones.GetDungeonBestLink(arg1) | function C_Keystones.GetDungeonBestLink(dungeonID) |
| GetKeystoneDungeonInfo | function | C_Keystones.GetKeystoneDungeonInfo(arg1) | local dungeonName, fileName, bestRun = C_Keystones.GetKeystoneDungeonInfo(dungeonID) |
| GetKeystoneInInventory | function | C_Keystones.GetKeystoneInInventory() | function C_Keystones.GetKeystoneInInventory() |
| GetKeystoneInInventoryItemID | function | C_Keystones.GetKeystoneInInventoryItemID() | local keystoneID = C_Keystones.GetKeystoneInInventoryItemID() |
| GetPlayerSaveKey | function | C_Keystones.GetPlayerSaveKey() | function C_Keystones.GetPlayerSaveKey() |
| GetProfileLink | function | C_Keystones.GetProfileLink(arg1) | function C_Keystones.GetProfileLink(expansion) |
| GetSetBest | function | C_Keystones.GetSetBest(arg1) | function C_Keystones.GetSetBest(affixSetString, expansion) |
| GetTimedDungeonsForExpansion | function | C_Keystones.GetTimedDungeonsForExpansion(arg1) | #C_Keystones.GetTimedDungeonsForExpansion(self.expansion) |
| MYTHIC_PLUS_COMPLETE | function | C_Keystones:MYTHIC_PLUS_COMPLETE(arg1) | function C_Keystones:MYTHIC_PLUS_COMPLETE(success) |
| MYTHIC_PLUS_COUNTDOWN_STARTED | function | C_Keystones:MYTHIC_PLUS_COUNTDOWN_STARTED(arg1) | function C_Keystones:MYTHIC_PLUS_COUNTDOWN_STARTED(seconds) |
| MYTHIC_PLUS_STARTED | function | C_Keystones:MYTHIC_PLUS_STARTED() | function C_Keystones:MYTHIC_PLUS_STARTED() |
| SaveKeystoneRun | function | C_Keystones.SaveKeystoneRun(arg1, arg2, arg3, arg4, arg5) | function C_Keystones.SaveKeystoneRun(dungeonID, finalTime, overtime, level, a) |
