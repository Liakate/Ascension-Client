# C_Cache



**Members:** 4  •  **Functions:** 2  •  **Interface calls:** 8 (across up to 3 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_Cache.lua` line 4




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| QueryAllStats | function | C_Cache:QueryAllStats(arg1) | C_Cache:QueryAllStats() |
| QueryStat | function | C_Cache:QueryStat(arg1, arg2) | function C_Cache:QueryStat(group, bypassCooldown) |
| LastStatQuery | number | C_Cache.LastStatQuery |  |
| Queried | table | C_Cache.Queried | C_Cache.Queried[v] = {} |
