# C_NamePlateManager



**Members:** 9  •  **Functions:** 9  •  **Interface calls:** 27 (across up to 3 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_NamePlateManager.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| ApplyFPSIncrease | function | C_NamePlateManager.ApplyFPSIncrease(arg1) | C_NamePlateManager.ApplyFPSIncrease(frame) |
| CheckNamePlateMotion | function | C_NamePlateManager.CheckNamePlateMotion() | setFunc = function() C_NamePlateManager.CheckNamePlateMotion() end, |
| DisableBlizzPlate | function | C_NamePlateManager.DisableBlizzPlate(arg1) | C_NamePlateManager.DisableBlizzPlate(unit) |
| EnumerateActiveNamePlates | function | C_NamePlateManager.EnumerateActiveNamePlates() | for frame in C_NamePlateManager.EnumerateActiveNamePlates() do |
| GetNamePlateSize | function | C_NamePlateManager.GetNamePlateSize() | unitFrame:SetSize(C_NamePlateManager.GetNamePlateSize()) |
| IsNamePlateMoving | function | C_NamePlateManager.IsNamePlateMoving(arg1) | function C_NamePlateManager.IsNamePlateMoving(nameplate) |
| RefreshNamePlateSize | function | C_NamePlateManager.RefreshNamePlateSize() | C_NamePlateManager.RefreshNamePlateSize() |
| SetEnableResizeNamePlates | function | C_NamePlateManager.SetEnableResizeNamePlates(arg1) | C_NamePlateManager.SetEnableResizeNamePlates(true) |
| SetNamePlateSize | function | C_NamePlateManager.SetNamePlateSize(arg1, arg2) | C_NamePlateManager.SetNamePlateSize(clickableWidth, clickableHeight) |
