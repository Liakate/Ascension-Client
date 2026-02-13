# C_Comm



**Members:** 15  •  **Functions:** 7  •  **Interface calls:** 10 (across up to 1 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `SharedXML/Util/C_Comm.lua` line 6




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| Enqueue | function | C_Comm:Enqueue(arg1, arg2) | function C_Comm:Enqueue(priority, message) |
| IsEmpty | function | C_Comm:IsEmpty() | function C_Comm:IsEmpty() |
| OnAttributeChanged | function | C_Comm:OnAttributeChanged(arg1, arg2) | function C_Comm:OnAttributeChanged(name, value) |
| OnUpdate | function | C_Comm:OnUpdate() | function C_Comm:OnUpdate() |
| SendJsonMessage | function | C_Comm:SendJsonMessage(arg1, arg2, arg3) | function C_Comm:SendJsonMessage(category, json, priority) |
| Setup | function | C_Comm:Setup() | function C_Comm:Setup() |
| UpdateAvailable | function | C_Comm:UpdateAvailable() | function C_Comm:UpdateAvailable() |
| HardThrottleStart | number | C_Comm.HardThrottleStart |  |
| LastAvailableUpdate | number | C_Comm.LastAvailableUpdate |  |
| available | number | C_Comm.available |  |
| elapsed | number | C_Comm.elapsed |  |
| Priority | table | C_Comm.Priority |  |
| Priority.BULK | table | C_Comm.Priority.BULK |  |
| Priority.NORMAL | table | C_Comm.Priority.NORMAL |  |
| Priority.URGENT | table | C_Comm.Priority.URGENT |  |
