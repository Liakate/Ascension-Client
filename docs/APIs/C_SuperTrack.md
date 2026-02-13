# C_SuperTrack



**Members:** 9  •  **Functions:** 9  •  **Interface calls:** 16 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ClearSuperTracker | function | C_SuperTrack.ClearSuperTracker() | C_SuperTrack.ClearSuperTracker() |
| GetSuperTrackedPosition | function | C_SuperTrack.GetSuperTrackedPosition() | local x, y, distance = C_SuperTrack.GetSuperTrackedPosition() |
| GetSuperTrackedWorldPosition | function | C_SuperTrack.GetSuperTrackedWorldPosition() |  |
| GetTargetState | function | C_SuperTrack.GetTargetState() | local state = C_SuperTrack.GetTargetState() |
| IsSuperTrackingAnything | function | C_SuperTrack.IsSuperTrackingAnything() | if C_SuperTrack.IsSuperTrackingAnything() then |
| PositionFrame | function | C_SuperTrack.PositionFrame(arg1) | C_SuperTrack.PositionFrame(true) |
| SetSuperTrackedCorpse | function | C_SuperTrack.SetSuperTrackedCorpse(arg1) | C_SuperTrack.SetSuperTrackedCorpse(true) |
| SetSuperTrackedPosition | function | C_SuperTrack.SetSuperTrackedPosition(arg1, arg2, arg3, arg4) | C_SuperTrack.SetSuperTrackedPosition(x, y, z, mapID) |
| SetSuperTrackedQuestID | function | C_SuperTrack.SetSuperTrackedQuestID(arg1) | C_SuperTrack.SetSuperTrackedQuestID(questID) |
