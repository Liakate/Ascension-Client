# C_ClassInfo



**Members:** 4  •  **Functions:** 4  •  **Interface calls:** 58 (across up to 14 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetAllSpecs | function | C_ClassInfo.GetAllSpecs(arg1) | specs = C_ClassInfo.GetAllSpecs(classFile) |
| GetClassBySpecName | function | C_ClassInfo.GetClassBySpecName(arg1) | if not C_ClassInfo.GetClassBySpecName then |
| GetSpecInfo | function | C_ClassInfo.GetSpecInfo(arg1, arg2) | specInfo = C_ClassInfo.GetSpecInfo(classFile, specName) |
| GetSpecInfoByID | function | C_ClassInfo.GetSpecInfoByID(arg1) | local specInfo = C_ClassInfo.GetSpecInfoByID(activeSpecID) |
