# C_RecoveryService



**Members:** 7  •  **Functions:** 7  •  **Interface calls:** 4 (across up to 1 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetCategoryItemAtIndex | function | C_RecoveryService.GetCategoryItemAtIndex(arg1, arg2) | self.item = C_RecoveryService.GetCategoryItemAtIndex(self.category, self.index) |
| GetNumItemsInCategory | function | C_RecoveryService.GetNumItemsInCategory(arg1) | return C_RecoveryService.GetNumItemsInCategory(self.currentCategory) or 0 |
| QueryCategory | function | C_RecoveryService.QueryCategory(arg1) | C_RecoveryService.QueryCategory(category) |
| RecoverCategoryItemAtIndex | function | C_RecoveryService.RecoverCategoryItemAtIndex(...) | local recoverFunc = GenerateClosure(C_RecoveryService.RecoverCategoryItemAtIndex, self.category, ... |
| SwapFactionChangePotion | function | C_RecoveryService.SwapFactionChangePotion(...) |  |
| SwapRaceChangePotion | function | C_RecoveryService.SwapRaceChangePotion(...) |  |
| UpdateFilter | function | C_RecoveryService.UpdateFilter(arg1, arg2) | C_RecoveryService.UpdateFilter(self.currentCategory, text) |
