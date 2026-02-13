# C_ContentLoader



**Members:** 4  •  **Functions:** 3  •  **Interface calls:** 5 (across up to 1 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Data/C_ContentLoader.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| AddToParseQueue | function | C_ContentLoader:AddToParseQueue(arg1) | function C_ContentLoader:AddToParseQueue(contentFile) |
| Load | function | C_ContentLoader:Load(arg1) | function C_ContentLoader:Load(file) |
| ResumeRoutines | function | C_ContentLoader:ResumeRoutines() | if not C_ContentLoader:ResumeRoutines() then |
| Runner | table | C_ContentLoader.Runner | C_ContentLoader.Runner = CreateFrame("Frame") |
