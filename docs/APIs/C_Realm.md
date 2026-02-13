# C_Realm



**Members:** 6  •  **Functions:** 6  •  **Interface calls:** 44 (across up to 22 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| IsDevelopment | function | C_Realm.IsDevelopment() | if C_Realm.IsDevelopment() then |
| IsLeague | function | C_Realm.IsLeague(...) |  |
| IsLive | function | C_Realm.IsLive() | if not C_Realm.IsLive() and not C_Realm.IsDevelopment() then |
| IsPTR | function | C_Realm.IsPTR() | self:SetShown(C_Realm.IsPTR()) |
| IsProduction | function | C_Realm.IsProduction(...) |  |
| IsSeasonal | function | C_Realm.IsSeasonal() | if C_Realm.IsSeasonal() then |



## Notes


- 2 member(s) had a runtime probe marked `ok` in the scan data.
