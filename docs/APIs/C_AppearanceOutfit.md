# C_AppearanceOutfit



**Members:** 6  •  **Functions:** 6  •  **Interface calls:** 9 (across up to 2 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| DeleteOutfit | function | C_AppearanceOutfit.DeleteOutfit(arg1) |  |
| GetAppearanceOutfits | function | C_AppearanceOutfit.GetAppearanceOutfits(...) |  |
| GetCurrentOutfitName | function | C_AppearanceOutfit.GetCurrentOutfitName() | if C_AppearanceOutfit.GetCurrentOutfitName() == self.outfitName then |
| GetOutfitInfo | function | C_AppearanceOutfit.GetOutfitInfo(arg1) | local appearanceIDs = C_AppearanceOutfit.GetOutfitInfo(self.outfitName) |
| SaveOutfit | function | C_AppearanceOutfit.SaveOutfit(arg1) |  |
| SetPendingOutfit | function | C_AppearanceOutfit.SetPendingOutfit(arg1) | C_AppearanceOutfit.SetPendingOutfit(self.outfitName) |



## Notes


- 1 member(s) had a runtime probe marked `ok` in the scan data.
