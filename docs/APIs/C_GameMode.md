# C_GameMode



**Members:** 22  •  **Functions:** 19  •  **Interface calls:** 111 (across up to 41 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_GameMode.lua` line 4




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ASCENSION_CUSTOM_GAME_MODE_CHANGED | function | C_GameMode:ASCENSION_CUSTOM_GAME_MODE_CHANGED() | function C_GameMode:ASCENSION_CUSTOM_GAME_MODE_CHANGED() |
| DoesFrameHaveEvent | function | C_GameMode.DoesFrameHaveEvent(...) |  |
| GenerateCallbackEvents | function | C_GameMode:GenerateCallbackEvents(arg1) | C_GameMode:GenerateCallbackEvents( |
| GetActiveGameModes | function | C_GameMode:GetActiveGameModes() | function C_GameMode:GetActiveGameModes() |
| GetCallbackTable | function | C_GameMode.GetCallbackTable(...) |  |
| GetCallbackTables | function | C_GameMode.GetCallbackTables(...) |  |
| GetCallbacksByEvent | function | C_GameMode.GetCallbacksByEvent(...) |  |
| HasRegistrantsForEvent | function | C_GameMode.HasRegistrantsForEvent(...) |  |
| IsAnyGameModeActive | function | C_GameMode:IsAnyGameModeActive() | function C_GameMode:IsAnyGameModeActive() |
| IsGameModeActive | function | C_GameMode:IsGameModeActive(arg1) | local isWildCard = C_GameMode:IsGameModeActive(Enum.GameMode.WildCard) |
| OnLoad | function | C_GameMode.OnLoad(...) |  |
| PLAYER_ENTERING_WORLD | function | C_GameMode:PLAYER_ENTERING_WORLD() | function C_GameMode:PLAYER_ENTERING_WORLD() |
| RegisterCallback | function | C_GameMode:RegisterCallback(arg1, arg2) | C_GameMode:RegisterCallback("OnGameModeChanged", GenerateClosure(self.OnGameModeChanged, self)) |
| RegisterCallbackWithHandle | function | C_GameMode:RegisterCallbackWithHandle(arg1, arg2) | self.gamemodeCallback = C_GameMode:RegisterCallbackWithHandle("OnGameModeChanged", GenerateClosu... |
| SecureInsertEvent | function | C_GameMode.SecureInsertEvent(...) |  |
| SetUndefinedEventsAllowed | function | C_GameMode.SetUndefinedEventsAllowed(...) |  |
| TriggerEvent | function | C_GameMode.TriggerEvent(...) |  |
| UnregisterCallback | function | C_GameMode.UnregisterCallback(...) |  |
| UnregisterEvents | function | C_GameMode.UnregisterEvents(...) |  |
| Event.OnGameModeChanged | string | C_GameMode.Event.OnGameModeChanged |  |
| Event | table | C_GameMode.Event |  |
| callbackTables | table | C_GameMode.callbackTables |  |



## Notes


- 3 member(s) had a runtime probe marked `ok` in the scan data.
