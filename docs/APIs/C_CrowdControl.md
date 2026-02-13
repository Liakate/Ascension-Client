# C_CrowdControl



**Members:** 9  •  **Functions:** 7  •  **Interface calls:** 9 (across up to 2 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_CrowdControl.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| HasControl | boolean | C_CrowdControl.HasControl |  |
| COMBAT_LOG_EVENT_UNFILTERED | function | C_CrowdControl:COMBAT_LOG_EVENT_UNFILTERED(arg1) | function C_CrowdControl:COMBAT_LOG_EVENT_UNFILTERED(...) |
| CROWD_CONTROL_ADDED | function | C_CrowdControl:CROWD_CONTROL_ADDED(arg1) | function C_CrowdControl:CROWD_CONTROL_ADDED(...) |
| CROWD_CONTROL_REMOVED | function | C_CrowdControl:CROWD_CONTROL_REMOVED(arg1) | function C_CrowdControl:CROWD_CONTROL_REMOVED(...) |
| GetActiveCrowdControl | function | C_CrowdControl:GetActiveCrowdControl() | function C_CrowdControl:GetActiveCrowdControl() |
| GetCrowdControlInfo | function | C_CrowdControl:GetCrowdControlInfo(arg1) | local name, icon, duration, expirationTime, startTime, priority, displayName, lockoutSchool = C_C... |
| PLAYER_ENTERING_WORLD | function | C_CrowdControl:PLAYER_ENTERING_WORLD() | function C_CrowdControl:PLAYER_ENTERING_WORLD() |
| UNIT_AURA | function | C_CrowdControl:UNIT_AURA(arg1) | function C_CrowdControl:UNIT_AURA(unit) |
| Active | table | C_CrowdControl.Active |  |
