# C_ExtraActionButton



**Members:** 3  •  **Functions:** 3  •  **Interface calls:** 5 (across up to 1 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetExtraActionButtonAtIndex | function | C_ExtraActionButton.GetExtraActionButtonAtIndex(arg1) | local buttonID = C_ExtraActionButton.GetExtraActionButtonAtIndex(i) |
| GetExtraActionButtonInfo | function | C_ExtraActionButton.GetExtraActionButtonInfo(arg1) | local actionType, actionName, actionID, art = C_ExtraActionButton.GetExtraActionButtonInfo(buttonID) |
| GetNumExtraActionButtons | function | C_ExtraActionButton.GetNumExtraActionButtons() | local numButtons = C_ExtraActionButton.GetNumExtraActionButtons() |
