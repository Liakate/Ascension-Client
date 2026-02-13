# C_PopupQueue



**Members:** 5  •  **Functions:** 2  •  **Interface calls:** 6 (across up to 4 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_PopupQueue.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| Add | function | C_PopupQueue:Add(arg1, arg2, arg3) | C_PopupQueue:Add(self, function() self:GoToTab(Collections.Tabs.CharacterAdvancement) end, functi... |
| AddAchievement | function | C_PopupQueue:AddAchievement(arg1) | function C_PopupQueue:AddAchievement(id) |
| Achievements | table | C_PopupQueue.Achievements | if #C_PopupQueue.Achievements > 0 then |
| Frame | table | C_PopupQueue.Frame | C_PopupQueue.Frame = CreateFrame("Frame") |
| Queue | table | C_PopupQueue.Queue | local item = C_PopupQueue.Queue[1] |
